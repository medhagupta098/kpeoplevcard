find_package(Qt5Test)

ecm_add_test(kpeoplevcardtest.cpp ../src/kpeoplevcard.cpp TEST_NAME kpeoplevcardtest LINK_LIBRARIES KF5::PeopleBackend KF5::CoreAddons Qt5::Test KF5::Contacts KF5::I18n)
