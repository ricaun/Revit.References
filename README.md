# Revit.References

References to Revit 2019 to 2022 assemblies.

## Revit 2022

### D2022
``` xml
  <PropertyGroup Condition="'$(Configuration)|$(Platform)' == 'D2022|x64'">
    <TargetFrameworkVersion>v4.8</TargetFrameworkVersion>
    <DebugSymbols>true</DebugSymbols>
    <OutputPath>bin\x64\$(Configuration)\</OutputPath>
    <DefineConstants>TRACE;DEBUG;Revit2022</DefineConstants>
    <DebugType>full</DebugType>
    <PlatformTarget>x64</PlatformTarget>
    <LangVersion>7.3</LangVersion>
    <ErrorReport>prompt</ErrorReport>
    <CodeAnalysisRuleSet>MinimumRecommendedRules.ruleset</CodeAnalysisRuleSet>
    <Prefer32Bit>true</Prefer32Bit>
  </PropertyGroup>
```

### R2022
``` xml
  <PropertyGroup Condition="'$(Configuration)|$(Platform)' == 'R2022|x64'">
    <TargetFrameworkVersion>v4.8</TargetFrameworkVersion>
    <OutputPath>bin\Content\R2022\</OutputPath>
    <DefineConstants>TRACE;Revit2022</DefineConstants>
    <Optimize>true</Optimize>
    <DebugType>pdbonly</DebugType>
    <PlatformTarget>x64</PlatformTarget>
    <ErrorReport>prompt</ErrorReport>
    <CodeAnalysisRuleSet>MinimumRecommendedRules.ruleset</CodeAnalysisRuleSet>
    <Prefer32Bit>true</Prefer32Bit>
  </PropertyGroup>
```

### Open Revit 2022
``` xml
  <PropertyGroup Condition="$(Configuration.Contains('2022'))">
    <StartAction>Program</StartAction>
    <StartProgram>C:\Program Files\Autodesk\Revit 2022\Revit.exe</StartProgram>
  </PropertyGroup>
```

### Reference 2022
``` xml
  <ItemGroup Condition="$(Configuration.Contains('2022'))">
    <Reference Include="AdWindows">
      <HintPath>$(SolutionDir)\packages\Revit.References\lib\Revit 2022\AdWindows.dll</HintPath>
      <Private>false</Private>
    </Reference>
    <Reference Include="NewtonSoft.Json">
      <HintPath>$(SolutionDir)\packages\Revit.References\lib\Revit 2022\NewtonSoft.Json.dll</HintPath>
      <Private>false</Private>
    </Reference>
    <Reference Include="RevitAPI">
      <HintPath>$(SolutionDir)\packages\Revit.References\lib\Revit 2022\RevitAPI.dll</HintPath>
      <Private>false</Private>
    </Reference>
    <Reference Include="RevitAPIIFC">
      <HintPath>$(SolutionDir)\packages\Revit.References\lib\Revit 2022\RevitAPIIFC.dll</HintPath>
      <Private>false</Private>
    </Reference>
    <Reference Include="RevitAPIUI">
      <HintPath>$(SolutionDir)\packages\Revit.References\lib\Revit 2022\RevitAPIUI.dll</HintPath>
      <Private>false</Private>
    </Reference>
    <Reference Include="UIFramework">
      <HintPath>$(SolutionDir)\packages\Revit.References\lib\Revit 2022\UIFramework.dll</HintPath>
      <Private>false</Private>
    </Reference>
  </ItemGroup>
```