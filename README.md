# Gitlab Merge Request Builder Plugin

A plugin that allows Hudson to build merge requests.

This plugin fetches the source and target branches of a Gitlab merge request and makes them available
to your build via build parameters. Once the build completes, Jenkins/Hudson will leave a comment on the merge
request indicating whether the merge request was successful.

