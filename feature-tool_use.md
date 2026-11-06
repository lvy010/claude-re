## core_feature_find

"tool_use": 121 matching strings, 0 matching function names, 0 matching imports; 0 functions involved.

- Evidence: `ev_25aa190b30dc3eee3872a3b3d84c3166aec44d322b79cbb10d752e2a4e7c8510`
- Confidence: derived
- Limitations:
  - nothing matched; the text may be built at run time, encrypted, or come from a resource file (absence is not proof)

```json
{
  "case_sensitive": false,
  "function_names": [],
  "functions": [],
  "imports": [],
  "query": "tool_use",
  "strings": [
    {
      "address": "0x104d778cc",
      "references": [],
      "text": "Forward subagent text and thinking blocks as assistant/user messages with parent_tool_use_id set (only works with --print and --output-format=stream-json)"
    },
    {
      "address": "0x104d7f488",
      "references": [],
      "text": "parent_tool_use_id"
    },
    {
      "address": "0x104d912c0",
      "references": [],
      "text": "tool_use_id"
    },
    {
      "address": "0x104d9b88c",
      "references": [],
      "text": "tool_use\n"
    },
    {
      "address": "0x104da0694",
      "references": [],
      "text": "tool_use_summary"
    },
    {
      "address": "0x104da4aec",
      "references": [],
      "text": "tool_use_result"
    },
    {
      "address": "0x104da6738",
      "references": [],
      "text": "peer_tool_use_omitted"
    },
    {
      "address": "0x104e1f504",
      "references": [],
      "text": "[sdkMessageAdapter] Dropping tool_progress frame with a non-string tool_name/tool_use_id or non-finite elapsed_time_seconds"
    },
    {
      "address": "0x104e1fb68",
      "references": [],
      "text": "[sdkMessageAdapter] Ignoring tool_use_summary message"
    },
    {
      "address": "0x104e20584",
      "references": [],
      "text": "tool_use_cleared_count"
    },
    {
      "address": "0x104e275dc",
      "references": [],
      "text": "server_tool_use"
    },
    {
      "address": "0x104e275f4",
      "references": [],
      "text": "mcp_tool_use"
    },
    {
      "address": "0x104e29eac",
      "references": [],
      "text": "after_tool_use"
    },
    {
      "address": "0x104e2f05c",
      "references": [],
      "text": "deferred_tool_use"
    },
    {
      "address": "0x104e5308c",
      "references": [],
      "text": "invalid_tool_use_id"
    },
    {
      "address": "0x104e9ac08",
      "references": [],
      "text": "grouped_tool_use"
    },
    {
      "address": "0x104eb76fc",
      "references": [],
      "text": "tool_use_error"
    },
    {
      "address": "0x104ebf10c",
      "references": [],
      "text": "^\\s*<tool_use_error>([\\s\\S]*)<\\/tool_use_error>\\s*$"
    },
    {
      "address": "0x104ebf148",
      "references": [],
      "text": "<\\/?tool_use_error\\b"
    },
    {
      "address": "0x104eceee4",
      "references": [],
      "text": "Input to command is JSON with tool_name, tool_input, tool_use_id, error, error_type, is_interrupt, and is_timeout.\nExit code 0 - stdout shown in transcript mode (ctrl+o)\nExit code 2 - show stderr to model immediately\nOther exit codes - show stderr to user only$"
    },
    {
      "address": "0x104ecf01c",
      "references": [],
      "text": "Fires once after every tool call in a batch has resolved, before the next model request. Input includes tool_calls (array of {tool_name, tool_input, tool_use_id, tool_response}).\nReturn additionalContext via hookSpecificOutput to inject context once for the whole batch.\nExit code 2 - stop the agentic loop (stderr shown to user only)\nOther exit codes - show stderr to user only"
    },
    {
      "address": "0x104ecf1d8",
      "references": [],
      "text": "Input to command is JSON with tool_name, tool_input, tool_use_id, and reason.\nReturn {\"hookSpecificOutput\":{\"hookEventName\":\"PermissionDenied\",\"retry\":true}} to tell the model it may retry.\nExit code 0 - stdout shown in transcript mode (ctrl+o)\nOther exit codes - show stderr to user only"
    },
    {
      "address": "0x104ed012c",
      "references": [],
      "text": "Input to command is JSON with tool_name, tool_input, and tool_use_id.\nOutput JSON with hookSpecificOutput containing decision to allow or deny.\nExit code 0 - use hook decision if provided\nOther exit codes - show stderr to user only"
    },
    {
      "address": "0x104f3d550",
      "references": [],
      "text": " tool_use name="
    },
    {
      "address": "0x104f50200",
      "references": [],
      "text": "malformed_tool_use_exhausted"
    },
    {
      "address": "0x104f525d8",
      "references": [],
      "text": "set_in_progress_tool_use_ids"
    },
    {
      "address": "0x104f52a78",
      "references": [],
      "text": "CLAUDE_CODE_EMIT_TOOL_USE_SUMMARIES"
    },
    {
      "address": "0x104f53904",
      "references": [],
      "text": "<tool_use_error>Error: No such tool available: "
    },
    {
      "address": "0x104f5393c",
      "references": [],
      "text": "</tool_use_error>"
    },
    {
      "address": "0x104f53a20",
      "references": [],
      "text": "<tool_use_error>Cancelled: Claude ended the conversation</tool_use_error>"
    },
    {
      "address": "0x104f53a98",
      "references": [],
      "text": "<tool_use_error>Error: Streaming fallback - tool execution discarded</tool_use_error>"
    },
    {
      "address": "0x104f547e4",
      "references": [],
      "text": "tool_use_summary_generation"
    },
    {
      "address": "0x104f54808",
      "references": [],
      "text": "summary_tool_use_generate"
    },
    {
      "address": "0x104f5482c",
      "references": [],
      "text": "tool_use_summary_generation_failed"
    },
    {
      "address": "0x104f58460",
      "references": [],
      "text": "malformed_tool_use_retry&"
    },
    {
      "address": "0x104f58480",
      "references": [],
      "text": "tengu_malformed_tool_use_retry_outcome"
    },
    {
      "address": "0x104f58678",
      "references": [],
      "text": "tengu_malformed_tool_use_response"
    },
    {
      "address": "0x104f59980",
      "references": [],
      "text": "tombstoned_had_tool_use"
    },
    {
      "address": "0x104f59e14",
      "references": [],
      "text": "salvaged_tool_use_count"
    },
    {
      "address": "0x104f59e50",
      "references": [],
      "text": "had_empty_input_tool_use\r"
    },
    {
      "address": "0x104f66b64",
      "references": [],
      "text": "^(?:<tool_use_error>)?\\s*"
    },
    {
      "address": "0x104faafc4",
      "references": [],
      "text": "Page text. PostToolUse hooks get it; tool_use_result does not."
    },
    {
      "address": "0x104fb4cc8",
      "references": [],
      "text": "\ntool_uses: "
    },
    {
      "address": "0x104fb6d34",
      "references": [],
      "text": "tool_uses"
    },
    {
      "address": "0x104fb87fc",
      "references": [],
      "text": "tool_use:"
    },
    {
      "address": "0x104fc13ac",
      "references": [],
      "text": "tool_use_ids"
    },
    {
      "address": "0x104fc1434",
      "references": [],
      "text": "invalid_handoff: tool_use_ids repeat%"
    },
    {
      "address": "0x104fc1560",
      "references": [],
      "text": " holds a tool_use block"
    },
    {
      "address": "0x104fc1580",
      "references": [],
      "text": "invalid_handoff: tool_use "
    },
    {
      "address": "0x104fc1bd4",
      "references": [],
      "text": " answers no earlier tool_use in the turn0"
    },
    {
      "address": "0x104fc1e48",
      "references": [],
      "text": "safeguard_tool_use is absent, malformed or too large"
    },
    {
      "address": "0x104fc1f30",
      "references": [],
      "text": "safeguard_tool_use"
    },
    {
      "address": "0x105042b8c",
      "references": [],
      "text": "tool_use_single"
    },
    {
      "address": "0x105044854",
      "references": [],
      "text": "tengu_tool_use_cancelled"
    },
    {
      "address": "0x105044c90",
      "references": [],
      "text": "tengu_tool_use_show_permission_request"
    },
    {
      "address": "0x10510c068",
      "references": [],
      "text": "] Received tool_result without tool_use_id"
    },
    {
      "address": "0x10510cdf8",
      "references": [],
      "text": "Cannot destructure property 'tool_use_id' from null or undefined value"
    },
    {
      "address": "0x10510ce48",
      "references": [],
      "text": "] permission_request missing tool_use_id or request_id"
    },
    {
      "address": "0x10510ce88",
      "references": [],
      "text": "] Ignoring permission_request for unknown tool_use_id "
    },
    {
      "address": "0x10513aa64",
      "references": [],
      "text": "^<tool_use_error>"
    },
    {
      "address": "0x10513aa80",
      "references": [],
      "text": "<\\/tool_use_error>$"
    },
    {
      "address": "0x10513bdb8",
      "references": [],
      "text": "</subagent_tokens><tool_uses>"
    },
    {
      "address": "0x10513bde0",
      "references": [],
      "text": "</tool_uses><duration_ms>"
    },
    {
      "address": "0x10517ac0c",
      "references": [],
      "text": "tool_result blocks are not matching any tool_use from the previous message"
    },
    {
      "address": "0x10517ac60",
      "references": [],
      "text": "ids of tool_result blocks and tool_use blocks from previous message do not match("
    },
    {
      "address": "0x10519edf8",
      "references": [],
      "text": "no_tool_use_block"
    },
    {
      "address": "0x10519f494",
      "references": [],
      "text": "total_tool_uses"
    },
    {
      "address": "0x10519f624",
      "references": [],
      "text": " tool_use: "
    },
    {
      "address": "0x10519f9f8",
      "references": [],
      "text": "CLAUDE_CODE_MAX_TOOL_USE_CONCURRENCYL"
    },
    {
      "address": "0x10519ff18",
      "references": [],
      "text": "batch_tool_uses"
    },
    {
      "address": "0x1051a04f8",
      "references": [],
      "text": "preceding_tool_use_ids"
    },
    {
      "address": "0x1051a0574",
      "references": [],
      "text": " tool_use: its path cannot be resolved"
    },
    {
      "address": "0x1051a0f34",
      "references": [],
      "text": "tool_use_meta"
    },
    {
      "address": "0x1051a2158",
      "references": [],
      "text": "Deferred tool resume: tool_use "
    },
    {
      "address": "0x1051a23d4",
      "references": [],
      "text": "no_tool_use_id"
    },
    {
      "address": "0x1051a2470",
      "references": [],
      "text": " has no matching tool_use block"
    },
    {
      "address": "0x1051a407c",
      "references": [],
      "text": "handleHandedOffTurn: the turn does not end with an assistant message naming tool_uses to run; running nothing"
    },
    {
      "address": "0x1051a40f4",
      "references": [],
      "text": "handleHandedOffTurn: tool_use "
    },
    {
      "address": "0x1051a4198",
      "references": [],
      "text": "\" for tool_use "
    },
    {
      "address": "0x105299780",
      "references": [],
      "text": "dangerous_tool_use"
    },
    {
      "address": "0x1052a9e48",
      "references": [],
      "text": "\"type\":\"tool_use\""
    },
    {
      "address": "0x1052b05c0",
      "references": [],
      "text": "^(?:<tool_use_error>)?(?:Error: )?"
    },
    {
      "address": "0x1052cda1c",
      "references": [],
      "text": "added_tool_use_gettask"
    },
    {
      "address": "0x1052cda3c",
      "references": [],
      "text": "added_tool_use_poll"
    },
    {
      "address": "0x1052cda58",
      "references": [],
      "text": "added_tool_use_other"
    },
    {
      "address": "0x1052cda74",
      "references": [],
      "text": "dropped_tool_use\n"
    },
    {
      "address": "0x1053158bc",
      "references": [],
      "text": "tengu_reorder_tool_uses_skipped_for_thinking"
    },
    {
      "address": "0x10531f97c",
      "references": [],
      "text": "unexpected `tool_use_id` found in `tool_result`"
    },
    {
      "address": "0x105320534",
      "references": [],
      "text": "tengu_tool_use_error,"
    },
    {
      "address": "0x105328528",
      "references": [],
      "text": "No tool_use blocks found in assistant message for fork directive: "
    },
    {
      "address": "0x105336820",
      "references": [],
      "text": "tengu_duplicate_tool_use_id"
    },
    {
      "address": "0x105336844",
      "references": [],
      "text": "API Error: 400 duplicate tool_use ID in conversation history."
    },
    {
      "address": "0x1053378e4",
      "references": [],
      "text": " overlong tool_use "
    },
    {
      "address": "0x105338038",
      "references": [],
      "text": "tengu_tool_use_not_loaded_check_failed"
    },
    {
      "address": "0x10533bdc4",
      "references": [],
      "text": "tengu_tool_use_granted_in_config"
    },
    {
      "address": "0x10533be14",
      "references": [],
      "text": "tengu_tool_use_granted_by_classifier*"
    },
    {
      "address": "0x10533be40",
      "references": [],
      "text": "tengu_tool_use_granted_in_prompt_permanent"
    },
    {
      "address": "0x10533be74",
      "references": [],
      "text": "tengu_tool_use_granted_in_prompt_temporary"
    },
    {
      "address": "0x10533bec8",
      "references": [],
      "text": "tengu_tool_use_granted_by_permission_hook"
    },
    {
      "address": "0x10533f650",
      "references": [],
      "text": ") left off the result message; tool_use_result.structuredContentOmitted is set, and content and resourceLinks are kept. "
    },
    {
      "address": "0x105348868",
      "references": [],
      "text": "`tool_use` ids were found without `tool_result` blocks immediately after"
    },
    {
      "address": "0x1053525bc",
      "references": [],
      "text": "tengu_pre_tool_use_refused_unfinished_hook"
    },
    {
      "address": "0x1053551e0",
      "references": [],
      "text": "tengu_tool_use_denied_in_config"
    },
    {
      "address": "0x10535522c",
      "references": [],
      "text": "tengu_tool_use_rejected_in_prompt"
    },
    {
      "address": "0x105362bc4",
      "references": [],
      "text": "tool_use_mismatch"
    },
    {
      "address": "0x105362c00",
      "references": [],
      "text": "duplicate_tool_use_id"
    },
    {
      "address": "0x105362d34",
      "references": [],
      "text": ".tool_use_id"
    },
    {
      "address": "0x105362d6c",
      "references": [],
      "text": "tool_use_id_invalid"
    },
    {
      "address": "0x105367854",
      "references": [],
      "text": "Extracted page images, in page order. Present only transiently in-process: the page image bytes are delivered solely as image blocks in the model-facing tool_result content and are not retained on the tool_use_result, so this key is absent on the emitted/persisted result"
    },
    {
      "address": "0x105367d8c",
      "references": [],
      "text": "ensureToolResultPairing: tool_use/tool_result pairing mismatch detected (strict mode). "
    },
    {
      "address": "0x10536af78",
      "references": [],
      "text": "tengu_tool_use_tool_result_mismatch_error"
    },
    {
      "address": "0x10536b9b0",
      "references": [],
      "text": "no call with that tool_use_id is open"
    },
    {
      "address": "0x105384be0",
      "references": [],
      "text": "> carrying this tool_use_id. Do not repeat the call, and do not wait, sleep or poll for it. You cannot stop it either, so never say you cancelled or dropped it."
    },
    {
      "address": "0x10538fff0",
      "references": [],
      "text": "`tool_use` ids must be unique"
    },
    {
      "address": "0x1053ab21c",
      "references": [],
      "text": "<tool_use_error>"
    },
    {
      "address": "0x1053b2fd4",
      "references": [],
      "text": "takes the tool_use_id of an open call"
    },
    {
      "address": "0x1053b8950",
      "references": [],
      "text": "\"tool_use_id\":\""
    },
    {
      "address": "0x1053be228",
      "references": [],
      "text": "tengu_tool_use_not_loaded"
    },
    {
      "address": "0x1053be2a0",
      "references": [],
      "text": "tengu_tool_use_isolation_latch_denied"
    },
    {
      "address": "0x1053d3210",
      "references": [],
      "text": "tool_use name is over the API's ."
    },
    {
      "address": "0x1053d5114",
      "references": [],
      "text": "tengu_tool_use_diff_computed"
    }
  ],
  "truncated": false
}
```

