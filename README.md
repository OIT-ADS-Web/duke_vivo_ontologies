# Duke-specific VIVO Ontologies

This is based on VIVO 1.5 and will probably change significantly when we migrate to VIVO 1.6.

1.  Duke Extensions:  Additions and modifications to identify Duke-specific data that is not otherwise defined in ontologies provided.
2.  Duke Artistic Works:  Defines the Artistic Works domain.
3.  Duke Geographic Focus:  Defines the 3 categories of geographic focus: research, teaching, or expertise.

This set of ontologies is used by both the Scholars@Duke (Vivo) application as well as the Vivo Administration tool (Ruby on Rails application).

## Installation

VIVO Admin: Put these files in config/ontologies directory along with the other Vivo-provided owl files.  All files with .owl suffix are automatically pulled into vivo_admin.  
Scholars@Duke: Put these files in productMods/WEB-INF/filegraph/tbox directory along with the other Vivo-provided ontologies.

