# Jekyll Resume template

_A simple Jekyll + GitHub Pages powered resume template._

![img](images/screenshot.png)

## Docs

### Running locally

To test locally, run the following in your terminal:

1.  Clone repo locally
2.  Run docker locally

```sh
export JEKYLL_VERSION=4
docker run --rm \
  -p 4000:4000 \
  --volume="$PWD:/srv/jekyll" \
  --volume="$PWD/_vendor/bundle:/usr/local/bundle" \
  -it jekyll/jekyll:$JEKYLL_VERSION \
  jekyll serve -H 0.0.0.0
# docker run --rm -p 4000:4000 --volume="$PWD/_vendor/bundle:/usr/local/bundle" --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:4 jekyll serve -H 0.0.0.0
```

#### Options/configuration

Most of the basic customization will take place in the `/_config.yml` file. Here is a list of customizations available via `/_config.yml`:

[...write these out...]

#### Editing content

Most of the content configuration will take place in the `/_layouts/resume.html` file. Simply edit the markup there accordingly

# License

The code and styles are licensed under the MIT license. [See project license.](LICENSE) Obviously you should not use the content of this demo repo in your own resume. :wink:

Disclaimer: Use of Homer J. Simpson image and name used under [Fair Use](https://en.wikipedia.org/wiki/Fair_use) for educational purposes. Project license does not apply to use of this material.
