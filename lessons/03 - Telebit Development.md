# Telebit Development

This lesson teaches how to use Telebit as a static web page server to allow seeing changes on in a website without needing to push to your GitHub Pages repo.

## Prerequisits

* [Telebit](https://telebit.cloud/)

## Work

Find the path to your repo. In your terminal you can type `pwd` if you are there.

Start telebit as a webserver. This command adds a subdomain `gp` to your telebit URL that staticly hosts your html pages.

```bash
telebit http <path/to/your/repo> gp
```

Ensure that telebit is working

```bash
telebit status
telebit enable
```

Navigate your new telebit site. It should have been listed in in the `status` call. When you change your files, you just need to refresh the page and your changes appear.
