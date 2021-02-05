# WSU Reuther ArchivesSpace Staff Interface Customizations

This ArchivesSpace plugins includes customizations to the Wayne State University Library's ArchivesSpace Staff Interface.

## Installation

Clone this repository to `/path/to/archivesspace/plugins` and enable the plugin by editing the `/path/to/archivesspace/config/config.rb`:

```
AppConfig[:plugins] = ['reuther_aspace_frontend_customizations']
```

## How it Works

This plugin modifies some of the default English language translations for the ArchivesSpace Staff Interface in `frontend/locales/en.yml` and overrides the default ArchivesSpace footer at `frontend/views/site/_footer.html.erb` to add a link to the Reuther's processing manual.