# App_PSTree-nodaliser

A "nodalised" fork of [splunk_pstree_app](https://github.com/murchisd/splunk_pstree_app).

* `pstree-for-splunk_210.tgz` — the original upstream app package (ASCII-art `tree` output), kept for reference.
* `splunk_pstree_nodaliser_app/` — the new app: the `pstree_node` command emits one row per parent/child edge with depth and full ancestor lineage, ready to feed a force-directed graph or dendrogram. (Named `pstree_node`, not `pstree`, to avoid clashing with the unrelated `pstree` command from other Splunkbase apps.) See `splunk_pstree_nodaliser_app/README.md` for usage.
