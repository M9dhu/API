# Documentation for Specification Linter

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *https://localhost:3000/v1*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AdminFunctionsApi* | [**addFunctions**](Apis/AdminFunctionsApi.md#addfunctions) | **POST** /admin/functions | Add functions
*AdminFunctionsApi* | [**deleteFunction**](Apis/AdminFunctionsApi.md#deletefunction) | **DELETE** /admin/functions/${functionName} | Delete a function
*AdminFunctionsApi* | [**updateFunction**](Apis/AdminFunctionsApi.md#updatefunction) | **PUT** /admin/functions/${functionName} | Update a function
*AdminLoggingApi* | [**getLogging**](Apis/AdminLoggingApi.md#getlogging) | **GET** /admin/logging | get logging
*AdminLoggingApi* | [**updateLogging**](Apis/AdminLoggingApi.md#updatelogging) | **PUT** /admin/logging | Update logging
*AdminRulesetsApi* | [**addRulesets**](Apis/AdminRulesetsApi.md#addrulesets) | **POST** /admin/rulesets | Add a rulesets
*AdminRulesetsApi* | [**deleteRuleset**](Apis/AdminRulesetsApi.md#deleteruleset) | **DELETE** /admin/rulesets/${rulesetName} | Delete a ruleset
*AdminRulesetsApi* | [**updateRuleset**](Apis/AdminRulesetsApi.md#updateruleset) | **PUT** /admin/rulesets/${rulesetName} | Update a ruleset
*FunctionsApi* | [**getFunction**](Apis/FunctionsApi.md#getfunction) | **GET** /functions/${functionName} | Get a function
*FunctionsApi* | [**getFunctions**](Apis/FunctionsApi.md#getfunctions) | **GET** /functions | Get the available functions
*LinterApi* | [**runLint**](Apis/LinterApi.md#runlint) | **POST** /linter | Lint the specification
*RulesetsApi* | [**getRuleset**](Apis/RulesetsApi.md#getruleset) | **GET** /rulesets/${rulesetName} | Get a ruleset
*RulesetsApi* | [**getRulesets**](Apis/RulesetsApi.md#getrulesets) | **GET** /rulesets | Get the available rulesets


<a name="documentation-for-models"></a>
## Documentation for Models

 - [Error](./\Models/Error.md)
 - [Function](./\Models/Function.md)
 - [FunctionDefinition](./\Models/FunctionDefinition.md)
 - [LintRequest](./\Models/LintRequest.md)
 - [LintResponse](./\Models/LintResponse.md)
 - [LintResponseRuleset](./\Models/LintResponseRuleset.md)
 - [LoggingDefinition](./\Models/LoggingDefinition.md)
 - [Result](./\Models/Result.md)
 - [Ruleset](./\Models/Ruleset.md)
 - [RulesetDefinition](./\Models/RulesetDefinition.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="api_key"></a>
### api_key

- **Type**: API key
- **API key parameter name**: api_key
- **Location**: HTTP header

