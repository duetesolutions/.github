# .github

Org-wide community health files for [Duete Solutions](https://duetesolutions.com).

GitHub uses this repository to provide **default** templates and community files
for every repo in the organization that doesn't define its own. Any repo can
override these by adding its own version of a file.

## What's here

| Path | Purpose |
| ---- | ------- |
| `profile/README.md` | Renders on the org profile page (github.com/duetesolutions) |
| `profile/assets/` | Images used by the profile README (logo, etc.) |
| `.github/PULL_REQUEST_TEMPLATE.md` | Default PR template |
| `.github/ISSUE_TEMPLATE/bug_report.md` | Default bug report form |
| `.github/ISSUE_TEMPLATE/feature_request.md` | Default feature request form |
| `.github/ISSUE_TEMPLATE/config.yml` | Issue template chooser config |

## How it works

- These files apply as **defaults** across all org repos. A repo that ships its
  own `.github/` file uses that one instead.
- Changes here take effect as soon as they land on the default branch — no
  release or publish step.
- `profile/README.md` is special: it only renders from this `.github` repo and
  drives the public org page.

## Contributing

Edits go through a PR against the default branch. The PR and issue templates in
this repo apply here too.
