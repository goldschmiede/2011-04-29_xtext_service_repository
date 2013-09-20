2011-04-29_xtext_service_repository
===================================

Service Modeling mit XtextServiceRepository

Als Voraussetzung solltet ihr Eclipse 3.6 for Java EE Developers installiert
haben (http://www.eclipse.org/downloads/). Zusätzlich müssen folgende
Plugins von der „Helios“ Update Site aus der Kategorie „Modeling“
installiert werden:
 
- Xpand SDK
- MWE 2 language SDK
- MWE 2 runtime SDK
- Xtext SDK 1.0.2
 
Wegen IP Issues ist auf der Helios Update Site leider ANTLR, das von Xtext
als Parser Generator verwendet wird nicht bereit gestellt. Diese holen wir
uns von dieser Update Site:
 
http://download.itemis.com/updates/
- Xtext Antlr SDK feature 1.0.1
 
Schließlich fehlen noch die Xtext Service Repository Plugins. Die könnt ihr
als gezippte Eclipse Update Site hier herunterladen:
https://github.com/downloads/andrearn/org.fornax.soa.xtextservicerepository/
XtextServiceRepository.zip
 
Einfach entpacken, als lokale Update Site in Eclipse einbinden und dann
installieren.
 
Falls wir noch Zeit haben, werden wir die Services auch mit CXF
implementieren. Dazu braucht ihr dann noch Maven 2 oder Maven 3 und einen
Tomcat 6.x. Für Eclipse gibt es hier auch ein Maven Plugin:
http://m2eclipse.sonatype.org/sites/m2e"
