spicy_add_analyzer(
    NAME Packet
    PACKAGE_NAME Packet
    SOURCES GOOSE.spicy GOOSE.evt zeek_GOOSE.spicy
    SCRIPTS __load__.zeek main.zeek dpd.sig)
