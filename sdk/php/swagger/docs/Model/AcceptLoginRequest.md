# AcceptLoginRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**acr** | **string** | ACR sets the Authentication AuthorizationContext Class Reference value for this authentication session. You can use it to express that, for example, a user authenticated using two factor authentication. | [optional] 
**remember** | **bool** | Remember, if set to true, tells ORY Hydra to remember this user by telling the user agent (browser) to store a cookie with authentication data. If the same user performs another OAuth 2.0 Authorization Request, he/she will not be asked to log in again. | [optional] 
**remember_for** | **int** | RememberFor sets how long the authentication should be remembered for in seconds. If set to &#x60;0&#x60;, the authorization will be remembered indefinitely. | [optional] 
**subject** | **string** | Subject is the user ID of the end-user that authenticated. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


