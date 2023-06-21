# Notes to myself, ignore if you are not me ^^

## TODO list for new releases
- [ ] Update `version = ` in `pyproject.toml`
- [ ] Run `jdappstreamedit ~/work/karoto/packaging/page.codeberg.DrRac27.Karoto.metainfo.xml` and add a new release
- [ ] Commit and tag. Push *both* - not just the commit
- [ ] Update the AUR package
- [ ] Update the pip package using `poetry publish -u DrRac27 --build`. On the OnePlus 6 I am already logged in, if not log in via `poetry config pypi-token.pypi pypi-ABCDEFG....LongStringThatIsTheTokenYouGetFromPyPi`
- [ ] Update the flatpak manifest (not the .tar.gz from pypi but the wheel...)
- [ ] Build the flatpak: `flatpak-builder --user --install --force-clean build-dir page.codeberg.DrRac27.Karoto.yml`
- [ ] Run and test it: `flatpak run --user page.codeberg.DrRac27.Karoto`
- [ ] Commit the changes to a new branch, push and create a PR
- [ ] Check the build
- [ ] Merge the PR
- [ ] Delete the flatpak: `flatpak uninstall --user page.codeberg.DrRac27.Karoto`
- [ ] Install the pmOS package again


## Useful links
- https://github.com/flathub/flathub/wiki/App-Maintenance
