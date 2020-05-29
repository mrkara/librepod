# librepod
Dummy repo to gitpodify LibreOffice core

## Why a dummy repo?
Currently, GitPod fetched all the submodules of a repo while cloning, which makes LibreOffice core repo exceed context deadline because of the very slow translations repo.

So I'll try to use this repo to have GitPod support for LibreOffice for now, as a work-around. Hope is that the translations rapo gets optimizes/improved in terms of performance or GitPod let's us choose if we want the submodules fetched; then we can copy the related stuff from this repo to its actual place (libreoffice/core).
