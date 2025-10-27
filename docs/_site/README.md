# Prusawire Documentation Site README

This runs using 'just-the-docs' template that creates a simple static HTML website using Jekyll / GitHub pages.  This is the exact same system the Voron Design Team uses for docs.vorondesign.com.

## Formatting Guide 

https://just-the-docs.github.io/just-the-docs/

## Outstanding TODOs
- Setup temp deploy (see below) for demo site
- Show to Nomad and get feedback on direction to pursue.
- Setup permenant deploy settings for real site.

## Publishing the site on GitHub Pages

1.  If your created site is `YOUR-USERNAME/YOUR-SITE-NAME`, update `_config.yml` to:

    ```yaml
    title: YOUR TITLE
    description: YOUR DESCRIPTION
    theme: just-the-docs

    url: https://YOUR-USERNAME.github.io/YOUR-SITE-NAME

    aux_links: # remove if you don't want this link to appear on your pages
      Template Repository: https://github.com/YOUR-USERNAME/YOUR-SITE-NAME
    ```

2.  Push your updated `_config.yml` to your site on GitHub.

3.  In your repo on GitHub:
    - go to the `Settings` tab -> `Pages` -> `Build and deployment`, then select `Source`: `GitHub Actions`.
    - if there were any failed Actions, go to the `Actions` tab and click on `Re-run jobs`.

