LineageOS 22.2 Dora source preservation snapshot.
Five Sony trees are published as full source trees on Lineageos-22.2.
Tracked changes from other repo projects are binary-safe git diffs relative to
commit SHAs in modified-projects.tsv, with exact AOSP repo revisions in
manifest-pinned.xml when repo manifest succeeds. To restore an AOSP patch,
checkout its recorded base SHA and run git apply --check <patch>, then git apply.
Untracked source files are under untracked/<project-path>/<relative-path>.
Review skipped-untracked.tsv for changes that were NOT published.
This does NOT publish LineageOS platform upstream source copies; use repo sync
with lineage-22.2 plus manifest-pinned.xml and these patches to reproduce it.
The label v11 is a local validation label; source branch is Lineageos-22.2.
