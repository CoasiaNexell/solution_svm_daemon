# solution_svm_daemon

---------------------------------------------------------------------------------------------------------------
20191018
	ver : 2.8.9
	- fixed raw image view feature bug at one camera mode.
	
---------------------------------------------------------------------------------------------------------------
20190909
	ver : 2.8.8
	- added NX_AVM_GPIO_UNEXPOROT_EN definition at NX_CGpioControl.cpp.
	  (Android and QT don't enable this definition.)
	
---------------------------------------------------------------------------------------------------------------
20190903
	ver : 2.8.7
	- added raw image view feature.
	- added new client libary API. (nx_avm_client_cmd_scene_set_rawimage)
	- added new client tutorial. (tutorial_03_raw_image)
	
20190723
	ver : 2.8.6
	- support NXP5431.
	- changed mali libraries.
	
---------------------------------------------------------------------------------------------------------------
20190717
	ver : 2.8.5
	- changed data target board directory. (from svmdata to oem, product)
	
---------------------------------------------------------------------------------------------------------------
20190712
	ver : 2.8.4
	- deleted wrong assert message.
	
--------------------------------------------------------------------------------------------------------------- 
20190709 ver : 2.8.3
	- added daemon main camera count(1 or 4) argument(0 or no argument use default avm_config.txt).
	- nx_avm_client_cmd_system_connect return camera count.
	- added nx_avm_client_cmd_system_get_prop() at client library(for getting Daemon PID).
	- moved data/avm/avm_config_onecam.txt to data/avm/avm_onecam/avm_config_onecam.txt.
	- added bin/test_view_rawimage for calibration utility. 
