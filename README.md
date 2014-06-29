# PHP Info in Public

Just a basic phpinfo file for cloning into the default Homestead box. Skips a couple manual steps you'd usually have to do.

## Usage

While SSHed into the Homestead VM (default site config), do the following:

```
cd Code
git clone https://github.com/Swader/publicinfo
```

You should be able to refresh the default `homestead.app:8000` now and get PHP info, without having to have written the info index file manually.
