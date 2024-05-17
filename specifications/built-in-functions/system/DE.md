[comment]: # (Note: This documentation is generated dynamically in the build process.  To modify the contents, change the javadoc on the _invoke method of the BIF class)

# Function: `DE`

Delay evaluation of a string as an expression, when it is passed as a parameter to the IIf or Evaluate functions.

## Method Signature
```
DE(string=[string])
```
### Arguments

| Argument | Type | Required | Description | Default |
|----------|------|----------|-------------|---------|
| `string` | `string` | `true` | The string to delay evaluation of. | |
|----------|------|----------|-------------|---------|



## Examples

```
DE(string=[string])
```

## Related
  * [ApplicationRestart](ApplicationRestart.md)
  * [ApplicationStartTime](ApplicationStartTime.md)
  * [ApplicationStop](ApplicationStop.md)
  * [BoxAnnounce](BoxAnnounce.md)
  * [BoxAnnounceAsync](BoxAnnounceAsync.md)
  * [CallStackGet](CallStackGet.md)
  * [CreateGUID](CreateGUID.md)
  * [CreateObject](CreateObject.md)
  * [CreateUUID](CreateUUID.md)
  * [DebugBoxContexts](DebugBoxContexts.md)
  * [Dump](Dump.md)
  * [Duplicate](Duplicate.md)
  * [echo](echo.md)
  * [EncodeForHTML](EncodeForHTML.md)
  * [GetApplicationMetadata](GetApplicationMetadata.md)
  * [GetBaseTemplatePath](GetBaseTemplatePath.md)
  * [GetBoxContext](GetBoxContext.md)
  * [GetBoxRuntime](GetBoxRuntime.md)
  * [GetBoxVersionInfo](GetBoxVersionInfo.md)
  * [GetComponentMetadata](GetComponentMetadata.md)
  * [GetContextRoot](GetContextRoot.md)
  * [GetCurrentTemplatePath](GetCurrentTemplatePath.md)
  * [GetFileFromPath](GetFileFromPath.md)
  * [GetFunctionCalledName](GetFunctionCalledName.md)
  * [GetFunctionList](GetFunctionList.md)
  * [GetSystemSetting](GetSystemSetting.md)
  * [GetTempDirectory](GetTempDirectory.md)
  * [GetTickCount](GetTickCount.md)
  * [htmlEditFormat](htmlEditFormat.md)
  * [IIF](IIF.md)
  * [Invoke](Invoke.md)
  * [IsInstanceOf](IsInstanceOf.md)
  * [JavaCast](JavaCast.md)
  * [PagePoolClear](PagePoolClear.md)
  * [Print](Print.md)
  * [Println](Println.md)
  * [RunThreadInContext](RunThreadInContext.md)
  * [SessionInvalidate](SessionInvalidate.md)
  * [SessionRotate](SessionRotate.md)
  * [SessionStartTime](SessionStartTime.md)
  * [Sleep](Sleep.md)
  * [SystemExecute](SystemExecute.md)
  * [SystemOutput](SystemOutput.md)
  * [Test](Test.md)
  * [Throw](Throw.md)
  * [URLDecode](URLDecode.md)
  * [URLEncodedFormat](URLEncodedFormat.md)
  * [writeDump](writeDump.md)
  * [WriteLog](WriteLog.md)
  * [WriteOutput](WriteOutput.md)