jzy3d-extensions
================

This is the master repository for managing all Jzy3d optional extensions.
It is both a maven and git super module.

Extension modules
-----------------
- <a href="https://github.com/jzy3d/jzy3d-graphs">jzy3d-graphs</a> : extends Gephi toolkit and Jzy3d with <a href="http://www.jzy3d.org/plugins-graphs.php">3d graph layouts and a 3d graph charts</a>. 
- <a href="https://github.com/jzy3d/jzy3d-depthpeeling">jzy3d-depthpeeling</a> : an extension allowing <a href="http://www.jzy3d.org/plugin-depthpeeling.php">visually perfect transparency</a>
- <a href="https://github.com/jzy3d/jzy3d-svm-mapper">jzy3d-svm-mapper</a> : building tesselated surfaces out of a SVM regression model (also depends on <a href="https://github.com/jzy3d/jzy3d-tools-libsvm">jzy3d-tools-libsvm</a>, a clone of libsvm of utility wrappers and refactors)
- <a href="https://github.com/jzy3d/jzy3d-g2d">jzy3d-g2d</a> : a POC showing how to read projected geometries in order to render them with Java2d

Other extension modules
-----------------------
These extensions are not part of this master repository and should be retrieved independently:
- <a href="https://github.com/jzy3d/jzy3d-javafx">jzy3d-javafx</a>: a work in progress to study JavaFx
- <a href="https://github.com/jzy3d/glredbook">glredbook</a>: the famous Open GL Red Book examples ported to Java & JOGL2

Getting the sources
-----------------------------------
To clone the master repository:
- git clone git@github.com:jzy3d/jzy3d-master.git
- cd jzy3d-master
- git submodule init
- git submodule update

To get/update children projects:
- ./git_pull (= git pull --rebase on each project)

To push change on multiple projects:
- ./git_commit (= git add ., git add -u, git commit -m [arg] on each project)
- ./git_push (= git push on each project)
- git add, commit, push on master

<a href="http://git-scm.com/book/en/Git-Tools-Submodules">More help on git submodules</a>


License
--------------
New BSD

More information
--------------
http://www.jzy3d.org
