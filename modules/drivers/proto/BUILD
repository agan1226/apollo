package(default_visibility = ["//visibility:public"])

cc_proto_library(
    name = "sensor_proto",
    deps = [
        ":sensor_proto_lib",
    ],
)

proto_library(
    name = "sensor_proto_lib",
    srcs = [
        "conti_radar.proto",
        "delphi_esr.proto",
        "mobileye.proto",
    ],
    deps = [
        "//modules/common/proto:header_proto_lib",
        "//modules/drivers/conti_radar/proto:conti_radar_proto_lib",
    ],
)
