#
# Makefile for the QCOM spcific video device drivers
# based on V4L2.
#

obj-$(CONFIG_MSM_VIDC_V4L2)     += vidc/
obj-$(CONFIG_MSM_WFD) += wfd/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/
ifeq ($(CONFIG_SEC_A3_EUR_PROJECT),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_a3/
else ifeq ($(CONFIG_SEC_SERRANOVE_PROJECT),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_serranovexx/
else 
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
endif
obj-$(CONFIG_MSM_VPU) += vpu/
