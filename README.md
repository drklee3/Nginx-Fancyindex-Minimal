# Nginx-Fancyindex-Minimal

Just a simple [Nginx](https://www.nginx.org) Fancyindex theme.

## Usage

1. Install the Fancy Index module with Nginx by compiling it or installing via nginx-extras.
2. Add configuration options below into a server section in your Nginx config file.
3. Copy the fancyindex/ directory to the root of your site.
4. Restart or reload Nginx

## Configuration
Example additions to your configuration.

```
location / {
    fancyindex on;              # Enable fancy indexes.
    fancyindex_exact_size off;  # Output human-readable file sizes.
    fancyindex_header "/fancyindex/header.html";
    fancyindex_footer "/fancyindex/footer.html";
}
```

## Screenshots

![Example #1](http://i.imgur.com/5eHmJMo.png)