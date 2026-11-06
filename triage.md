## core_target_triage

claude is a program for Mac, built for arm64 (64-bit). Its internal names were removed (stripped), so most functions will have generated names.

- Evidence: `ev_0da801d0e316782715918ed8c25114ef14e0936caf29ae6103a1d89dba7efc60`
- Confidence: observed
- Limitations:
  - toolchain and packer hints come from markers that can be faked or borrowed

```json
{
  "architecture": "arm64",
  "bits": 64,
  "dotnet_arch": null,
  "entry_point": "0x1011459f0",
  "format": "mach-o",
  "format_name": "Mach-O (macOS, iOS)",
  "kind": "executable",
  "libraries": [
    "/usr/lib/libicucore.A.dylib",
    "/usr/lib/libresolv.9.dylib",
    "/usr/lib/libc++.1.dylib",
    "/usr/lib/libSystem.B.dylib"
  ],
  "next_steps": [
    {
      "tool": "core_overview_show",
      "why": "a one-page summary: sections, imports, counts"
    },
    {
      "tool": "native_functions_list",
      "why": "every function we found"
    },
    {
      "tool": "native_strings_find",
      "why": "find text the program shows or uses"
    },
    {
      "tool": "native_function_study",
      "why": "a full dossier on one function (start with main or the entry point)"
    },
    {
      "tool": "core_feature_find",
      "why": "follow a word you see in the app to the code behind it"
    },
    {
      "tool": "apple_objc_classes_list",
      "why": "Objective-C classes and their methods"
    },
    {
      "tool": "apple_macho_show",
      "why": "load commands, linked libraries, code signature"
    }
  ],
  "operating_system": "Mac",
  "plain_english": "claude is a program for Mac, built for arm64 (64-bit). Its internal names were removed (stripped), so most functions will have generated names.",
  "recommended_toolsets": [
    "core",
    "native",
    "apple"
  ],
  "stripped": true,
  "symbol_table_stripped": true,
  "toolchain_hints": []
}
```

