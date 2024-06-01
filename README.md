# Sync OpenHarmony docs

This is an internal helper repository which only contains a CI job which updates
https://github.com/openharmony-rs/openharmony-docs with the latest contents from
the upstream gitee repository. 
Scheduled GitHub actions only run on the main branch of a repository, so we need
to put this ci job in this dedicated repo.