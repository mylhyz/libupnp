include (GoogleTest)

UPNP_addGTest (test_template test_template.cpp
	ADDITIONAL_INCLUDE_DIRS ${CMAKE_CURRENT_SOURCE_DIR}/../upnp/src/threadutil/
)

#UPNP_addGTest (test_UpnpHttpHeaderList test_UpnpHttpHeaderList.cpp
#	ADDITIONAL_INCLUDE_DIRS ${CMAKE_CURRENT_SOURCE_DIR}/../upnp/src/threadutil/
#)

#if (NOT WIN32)
#	UPNP_addGTest (test_upnpapi test_upnpapi.cpp
#		ADDITIONAL_INCLUDE_DIRS ${CMAKE_CURRENT_SOURCE_DIR}/../upnp/src/threadutil/
#	)
#endif()
