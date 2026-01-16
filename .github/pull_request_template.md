## Summary

Describe what this PR changes and why.

## Checklist

- [ ] Scope is focused (one logical change set)
- [ ] No secrets included (API keys/tokens removed or redacted)
- [ ] Local checks run:
  - [ ] `python3 -m pytest -q test/test_bridge.py test/test_rate_limiter.py`
  - [ ] (optional) `python3 -m compileall -q semantic_scholar run.py`
- [ ] If behavior changes or new env vars were added, `README.md` was updated
- [ ] If a server/port is introduced or changed, it is configurable via env (enable/host/port)
- [ ] If HTTP code was touched, uses shared helpers in `semantic_scholar/utils/http.py`

## Testing Notes

If this requires `SEMANTIC_SCHOLAR_API_KEY` or hits real APIs, describe how you tested it and any rate-limit considerations.

