<h1 align="center">cakebuild.snk :key:</h1>
<div align="center">

Strong Name Key Pair used to sign assemblies of the Cake projects

</div>

### Public key (hash algorithm: sha1):
```
0024000004800000940000000602000000240000525341310004000001000100f11fa73311abdf
24cbb9b20f528a9d2b5d12a1485a4240f6ec93783869a3da88a2db961369f0e6da81bbc1ed823b
da5b2a4be7fd556ab63d5672149ac53d97c90e8fb845bf95004cdc7f0e2ea6c02220ca2299cf83
7c581f858cc1f7cd59dba599b09a7391618620313102f765532ad299390d20786c74a41c73ca4f
c90e54df
```

### Public key token
```
813837363a85b89d
```

### csproj

```xml
  <ItemGroup>
    <AssemblyAttribute Include="System.Runtime.CompilerServices.InternalsVisibleTo">
      <_Parameter1>ReplaceWithAssemblyName, PublicKey=0024000004800000940000000602000000240000525341310004000001000100f11fa73311abdf24cbb9b20f528a9d2b5d12a1485a4240f6ec93783869a3da88a2db961369f0e6da81bbc1ed823bda5b2a4be7fd556ab63d5672149ac53d97c90e8fb845bf95004cdc7f0e2ea6c02220ca2299cf837c581f858cc1f7cd59dba599b09a7391618620313102f765532ad299390d20786c74a41c73ca4fc90e54df</_Parameter1>
    </AssemblyAttribute>
  </ItemGroup>
```

### AssemblyInfo

```csharp
[assembly: InternalsVisibleTo("<ReplaceWithAssemblyName>, PublicKey=" +
    "0024000004800000940000000602000000240000525341310004000001000100f11fa73311abdf" +
    "24cbb9b20f528a9d2b5d12a1485a4240f6ec93783869a3da88a2db961369f0e6da81bbc1ed823b" +
    "da5b2a4be7fd556ab63d5672149ac53d97c90e8fb845bf95004cdc7f0e2ea6c02220ca2299cf83" +
    "7c581f858cc1f7cd59dba599b09a7391618620313102f765532ad299390d20786c74a41c73ca4f" +
    "c90e54df")]
```
