include $(THEOS)/makefiles/common.mk

BUNDLE_NAME = Invision
Invision_FILES = ivsnRootListController.m
Invision_INSTALL_PATH = /Library/PreferenceBundles
Invision_FRAMEWORKS = UIKit
Invision_PRIVATE_FRAMEWORKS = Preferences

include $(THEOS_MAKE_PATH)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/Invision.plist$(ECHO_END)
