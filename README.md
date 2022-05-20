# gitcheatsheet
## 1. Getting Started
### `git init`
#### `git init <directory>:`
<ul>
  <li>Creates a new Git repo. It can be used to convert an existing, unversioned project to a Git repo or initialize a new, empty one</li>
  <li>Basically, it creates a <code>.git</code> directory in <code>&ltdirectory&gt</code>  with subdirectories for <em>objects</em>, <em>refs/heads</em>, <em>refs/tags</em>, and template files. A <em>HEAD</em> file is also created which points to the currently checked out commit. If <code>&ltdirectory&gt</code> is not specified, it defaults to the current working directory <code>(.)</code></li>
    <li>Running <code>git init</code> on a versioned project does not reset the repo</li>
</ul>

