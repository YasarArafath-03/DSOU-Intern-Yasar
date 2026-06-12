# Day 3 Reflection

## Date
12 June 2026

## Which log format feels more readable?

Linux logs are more readable because they are plain text and easy to search using command-line tools.

### Windows (EVTX/XML) Readability

**Strengths**
- Structured format
- Detailed event information
- Easy SIEM integration

**Weaknesses**
- Difficult to read manually
- Larger event size
- Requires Event Viewer

### Linux (Plain Text Logs) Readability

**Strengths**
- Human readable
- Easy to search with grep
- Lightweight

**Weaknesses**
- Less structured
- Manual parsing required
- Different services use different formats

## My Personal Preference

I prefer Linux logs because they are simple, lightweight and easy to investigate quickly. Commands such as grep, tail and journalctl allow fast analysis without special tools.

## Example Comparison

### Reading a Windows 4624 Event

Windows provides structured XML fields such as Event ID, username, source IP address and process information.

### Reading a Linux auth.log Entry

Linux displays timestamp, process name, username and source IP directly in a single line.

## Conclusion

Both formats are useful. Windows logs provide richer structured data, while Linux logs are faster and easier for manual investigations.
