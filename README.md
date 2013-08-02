This repository is set up to allow me to easily initialize projects without dealing with boiler-plate cruft.

Nothing here is complicated enough to warrant a license, and you're free to do what you will with it. Any projects where this does not hold true have licenses alongside related files.

Expected workflow is:

    git clone git@github.com:wahjah/prj_skel.git
    rm -rf .git README.md
    git init
    git remote add origin git@github.com:<user>/<repo>
    git push -u origin master
