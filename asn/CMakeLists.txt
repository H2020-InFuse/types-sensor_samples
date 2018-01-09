# H2020 ESROCOS Project
# Company: GMV Aerospace & Defence S.A.U.
# Licence: GPLv2

esrocos_asn1_types_package(esrocos_types_sensor_samples 
        CompressedFrame.asn
        DepthMap.asn
        DistanceImage.asn
        Frame.asn
        IMUSensors.asn
        LaserScan.asn
        Pointcloud.asn
        Sonar.asn
        SonarBeam.asn
        SonarScan.asn
        IMPORT types/base)

esrocos_asn1_types_build_test(esrocos_types_sensor_samples)
esrocos_asn1_types_install(esrocos_types_sensor_samples ${CMAKE_INSTALL_PREFIX}/types/sensor_samples)


