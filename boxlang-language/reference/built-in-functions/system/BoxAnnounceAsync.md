[comment]: # (Note: This documentation is generated dynamically in the build process.  To modify the contents, change the javadoc on the _invoke method of the BIF class)

# Function: `BoxAnnounceAsync`

Announce a BoxLang event to the system asynchronously

## Method Signature

```
BoxAnnounceAsync(state=[string], data=[struct])
```

### Arguments


| Argument | Type | Required | Description | Default |
|----------|------|----------|-------------|---------|
| `state` | `string` | `true` | The event to announce |  |
| `data` | `struct` | `false` | The data to send with the event | `{}` |

## Examples



## Related

  * [ApplicationRestart](./ApplicationRestart.md)
  * [ApplicationStartTime](./ApplicationStartTime.md)
  * [ApplicationStop](./ApplicationStop.md)
  * [BoxAnnounce](./BoxAnnounce.md)
  * [BoxRegisterInterceptor](./BoxRegisterInterceptor.md)
  * [BoxRegisterRequestInterceptor](./BoxRegisterRequestInterceptor.md)
  * [CallStackGet](./CallStackGet.md)
  * [CreateGUID](./CreateGUID.md)
  * [CreateObject](./CreateObject.md)
  * [CreateUUID](./CreateUUID.md)
  * [DE](./DE.md)
  * [DebugBoxContexts](./DebugBoxContexts.md)
  * [Dump](./Dump.md)
  * [Duplicate](./Duplicate.md)
  * [echo](./echo.md)
  * [EncodeForHTML](./EncodeForHTML.md)
  * [GetApplicationMetadata](./GetApplicationMetadata.md)
  * [GetBaseTagData](./GetBaseTagData.md)
  * [GetBaseTagList](./GetBaseTagList.md)
  * [GetBaseTemplatePath](./GetBaseTemplatePath.md)
  * [GetBoxContext](./GetBoxContext.md)
  * [GetBoxRuntime](./GetBoxRuntime.md)
  * [GetBoxVersionInfo](./GetBoxVersionInfo.md)
  * [GetClassMetadata](./GetClassMetadata.md)
  * [GetComponentList](./GetComponentList.md)
  * [GetContextRoot](./GetContextRoot.md)
  * [GetCurrentTemplatePath](./GetCurrentTemplatePath.md)
  * [GetFileFromPath](./GetFileFromPath.md)
  * [GetFunctionCalledName](./GetFunctionCalledName.md)
  * [GetFunctionList](./GetFunctionList.md)
  * [GetModuleInfo](./GetModuleInfo.md)
  * [GetModuleList](./GetModuleList.md)
  * [GetSystemSetting](./GetSystemSetting.md)
  * [GetTempDirectory](./GetTempDirectory.md)
  * [GetTickCount](./GetTickCount.md)
  * [htmlEditFormat](./htmlEditFormat.md)
  * [IIF](./IIF.md)
  * [Invoke](./Invoke.md)
  * [IsInstanceOf](./IsInstanceOf.md)
  * [JavaCast](./JavaCast.md)
  * [ObjectDeserialize](./ObjectDeserialize.md)
  * [ObjectSerialize](./ObjectSerialize.md)
  * [PagePoolClear](./PagePoolClear.md)
  * [Print](./Print.md)
  * [Println](./Println.md)
  * [RunThreadInContext](./RunThreadInContext.md)
  * [SessionInvalidate](./SessionInvalidate.md)
  * [SessionRotate](./SessionRotate.md)
  * [SessionStartTime](./SessionStartTime.md)
  * [Sleep](./Sleep.md)
  * [SystemCacheClear](./SystemCacheClear.md)
  * [SystemExecute](./SystemExecute.md)
  * [SystemOutput](./SystemOutput.md)
  * [Throw](./Throw.md)
  * [URLDecode](./URLDecode.md)
  * [URLEncodedFormat](./URLEncodedFormat.md)
  * [writeDump](./writeDump.md)
  * [WriteLog](./WriteLog.md)
  * [WriteOutput](./WriteOutput.md)
