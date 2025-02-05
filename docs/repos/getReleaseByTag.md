---
name: Get a release by tag name
example: octokit.rest.repos.getReleaseByTag({ owner, repo, tag })
route: GET /repos/{owner}/{repo}/releases/tags/{tag}
scope: repos
type: API method
---

# Get a release by tag name

Get a published release with the specified tag.

```js
octokit.rest.repos.getReleaseByTag({
  owner,
  repo,
  tag,
});
```

## Parameters

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>required</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>owner</td><td>yes</td><td>

The account owner of the repository. The name is not case sensitive.

</td></tr>
<tr><td>repo</td><td>yes</td><td>

The name of the repository. The name is not case sensitive.

</td></tr>
<tr><td>tag</td><td>yes</td><td>

tag parameter

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://docs.github.com/rest/reference/repos#get-a-release-by-tag-name).
