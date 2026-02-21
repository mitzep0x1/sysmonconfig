# sysmonconfig


```
git clone https://github.com/mitzep0x1/sysmonconfig.git

cd sysmonconfig

git clone https://github.com/olafhartong/sysmon-modular.git

Copy-Item 7_image_load\* sysmon-modular\7_image_load\

Import-Module .\sysmon-modular\Merge-SysmonXml.ps1
Merge-AllSysmonXml -AsString -BasePath .\sysmon-modular\ | Out-File -Encoding utf8 sysmonconfig.xml
```