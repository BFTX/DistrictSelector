# DistrictSelector
# get province 、city、area js data dynamic

#initdata get province data
#data formate [{name:北京,id:110000},{name:天津，id:110001},....]
var TN={};
TN.DistrictSelector.initData();

#get district-data under parent_id
#data formate like up
TN.DistrictSelector.getData(parent_id);

#get name of id's
TN.DistrictSelector.getName(id);
