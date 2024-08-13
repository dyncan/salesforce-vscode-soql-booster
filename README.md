# Salesforce SOQL Booster

## Introduction

Salesforce SOQL Booster is a Visual Studio Code extension designed to enhance the efficiency of Salesforce developers when writing static SOQL (Salesforce Object Query Language) queries within Apex classes. This plugin offers intelligent field suggestions, dynamic object recognition, and cache management features, making SOQL query writing faster and more accurate.

## Demo 
![Demo 1](https://raw.githubusercontent.com/dyncan/salesforce-vscode-soql-booster/main/images/SOQL_Booster-Demo1.gif)

![Demo 2](https://raw.githubusercontent.com/dyncan/salesforce-vscode-soql-booster/main/images/SOQL_Booster-Demo2.gif)

---

## Key Features

- **Static SOQL Support**: Currently optimized for static SOQL queries within Apex classes.
- **Intelligent Field Suggestions**: Automatically suggests available fields based on the current Salesforce object.
- **Dynamic Object Recognition**: Identifies objects in static SOQL queries and provides relevant field suggestions.
- **Cache Management**: Caches field data for improved performance with an option for manual refresh.
- **Cross-Relationship Query Support**: Provides field suggestions in relationship queries.

## Prerequisites

- A Salesforce project authenticated with an org.
- Salesforce CLI installed and configured.
- Visual Studio Code (version 1.60.0 or higher).

## Installation

1. Open Visual Studio Code.
2. Go to the Extensions view (Ctrl+Shift+X / Cmd+Shift+X).
3. Search for "Salesforce SOQL Booster".
4. Click the "Install" button.

## Usage

1. Open an Apex class file in your authenticated Salesforce project.
2. Start writing a static SOQL query (within the `[SELECT ... FROM ...]` format).
3. The plugin will automatically identify the object based on the current cursor position and provide corresponding field suggestions.
4. Use Tab or Enter to accept suggestions.

Note: The plugin currently supports static SOQL queries within Apex classes only.

### Clearing the Cache

To refresh field data:

1. Select "Clear Salesforce Field Cache" from the suggestion list.
2. The cache will be cleared, and subsequent suggestions will use the latest field data.

## Configuration

Currently, the plugin does not require additional configuration. It automatically uses your Salesforce CLI configuration to connect to your org.

## Limitations

- The plugin is currently optimized for static SOQL queries within Apex classes.
- Dynamic SOQL or queries outside of Apex classes may not be fully supported.

## Troubleshooting

If you encounter issues:

1. Ensure your Salesforce CLI is correctly configured and can connect to your org.
2. Check that you're writing static SOQL queries within an Apex class.
3. Try clearing the field cache.

## Contact

For any questions, suggestions, or to report issues with static SOQL support, please create an issue or [contact us](mailto:soql.booster@outlook.com).