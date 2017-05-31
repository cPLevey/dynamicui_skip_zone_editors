# dynamicui_skip_zone_editors

The [Advanced Zone Editor][1] & [Simple Zone Editor][2] became deprecated in v62 (Reference: [Release Notes][3]). This dynamicui configuration file will remove the icons and interfaces from loading in the cPanel Paper Lantern interface. 

Official documentation for Dynamic UI files can be found here: [Guide to cPanel Plugins - The dynamicui Files][4]


## Use & Installation

### Manual

+ Create the `dynamicui_skip_zone_editors.conf` file in the `/usr/local/cpanel/base/frontend/paper_lantern/dynamicui` directory.
+ Copy the contents of `dynamicui_skip_zone_editors.conf` from this repository into the newly created file. 


### Copy & Paste

+ `curl -sL 'https://surl.host/dynamicconf' > /usr/local/cpanel/base/frontend/paper_lantern/dynamicui/dynamicui_skip_zone_editors.conf`


## Screenshots

### Before

![alt text][zone_before]

### After

![alt text][zone_after]




[1]: https://documentation.cpanel.net/display/ALD/Advanced+Zone+Editor
[2]: https://documentation.cpanel.net/display/ALD/Simple+Zone+Editor
[3]: https://documentation.cpanel.net/display/ALD/62+Release+Notes#id-62ReleaseNotes-SimpleZoneEditorandAdvancedZoneEditorcombinedintoZoneEditor
[4]: https://documentation.cpanel.net/display/SDK/Guide+to+cPanel+Plugins+-+The+dynamicui+Files

[zone_before]: https://github.com/cPLevey/dynamicui_skip_zone_editors/raw/master/screenshots/zone_before.png "Before"
[zone_after]: https://github.com/cPLevey/dynamicui_skip_zone_editors/raw/master/screenshots/zone_after.png "After"