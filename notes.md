# Canary-Domains-Conflict-Detection

From the brainstorming list:
- How might the canary domain be standardized? What would the name be? Do we need to use a current reserved name or work with IANA to setup a new universal name?
- How to detect the presence of a DNS re-writing service such as parental controls
- Should only be local and should be relative to server's locally scoped name (if that is even possible)
- E.g. canary-domain.forwarder-or-resolver-name.local (not literally, just semantically)
