# Project lessons

Read relevant entries before implementation, review, or acceptance. Record reusable lessons after an observed correction, rework, or missed acceptance case.
Only a template is recorded so far; this does not mean the project has never had problems.

## Entry template

Copy the template for a new lesson; update an existing entry for the same failure pattern. Mark unknown causes, commits, or acceptance results as unverified.
Count independently evidenced recurrences. Multiple repair commits or retries for one incident do not increase the count.
Keep reusable causes and evidence pointers here; keep credentials, private material, and full logs in their authorized locations.

```markdown
### <Lesson title>

**<One sentence stating the rule to follow next time.>**

- Cause and consequence: <Trigger, cause, user-visible impact, and introducing commit or issue; mark unknown facts as unverified.>
- Fix and evidence: <Fix commit or PR, regression check, and actual acceptance evidence; distinguish verified results from remaining gaps.>
- Done right: <Concrete future action; link to the safeguard in code, checks, or the owning standard.>
- Recurrence: Seen <N>x (<YYYY-MM-DD, ...>); <Evidence for each independent occurrence; exclude repair commits and retries.>
```
