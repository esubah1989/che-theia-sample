# Adding plugin to Che
- Repackage this file: https://github.com/esubah1989/che-theia-sample/releases/download/next/che-editor-plugin.tar.gz

- Upload the repackage file in a repo. Make sure this file can be downloaded just by clicking its url
- Clone this https://github.com/eclipse/che-plugin-registry
- Go into che-plugin-registry/plugins/org.eclipse.che.editor.theia/1.0.0/meta.yaml and edit it according to plugin config
  It should look similar to this  
  ``` id: org.eclipse.che.editor.theia 
    version: 1.0.0
   type: Che Editor
   name: theia-ide2
   title: Eclipse Theia for Eclipse Che
   description: Eclipse Theia
   icon: https://link/to/an/icon/you/want/to/use/for/your/plugin
   url: https://link/to/your/che-editor-plugin.tar.gz
  publisher: Red Hat, Inc.
  category: Editor
  repository: https://link/to/the/repository/where/your/tar/file/is
   firstPublicationDate: "year-day-month"
 ```
