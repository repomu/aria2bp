# aria2bp

A Heroku buildpack for aria2 that always downloads the latest static build.
Unlike other build packs, I never compile anything and remove this git.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/repomu/aria2bp.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/repomu/aria2bp.git
```
