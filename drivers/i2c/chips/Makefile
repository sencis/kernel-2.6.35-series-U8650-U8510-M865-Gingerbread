#
# Makefile for miscellaneous I2C chip drivers.
#
# Do not add new drivers to this directory! It is DEPRECATED.
#
# Device drivers are better grouped according to the functionality they
# implement rather than to the bus they are connected to. In particular:
# * Hardware monitoring chip drivers go to drivers/hwmon
# * RTC chip drivers go to drivers/rtc
# * I/O expander drivers go to drivers/gpio
#

#/* < DTS7X27K00120101103   M����mem��001��20101103 begin */
obj-$(CONFIG_SENSORS_AKM8973)	+= akm8973.o
obj-$(CONFIG_SENSORS_AKM8976)	+= akm8976.o
obj-$(CONFIG_DS1682)		+= ds1682.o
obj-$(CONFIG_SENSORS_PCA963X)	+= pca963x.o
obj-$(CONFIG_SENSORS_TSL2550)	+= tsl2550.o
obj-$(CONFIG_SENSORS_MT9T013)	+= mt9t013.o
obj-$(CONFIG_VP_A1026)		+= a1026.o
obj-$(CONFIG_HUAWEI_FEATURE_QWERTY_KEYPAD_ADP5587) += adp5587.o
obj-$(CONFIG_HUAWEI_FEATURE_SENSORS_ST_LSM303DLH) += st303_compass.o
obj-$(CONFIG_HUAWEI_FEATURE_SENSORS_ST_LSM303DLH) += st303_gs.o
#/* DTS7X27K00120101103   M����mem��001��20101103 end > */
obj-$(CONFIG_HUAWEI_FEATURE_SENSORS_AK8975)   += akm8975.o
ifeq ($(CONFIG_I2C_DEBUG_CHIP),y)
EXTRA_CFLAGS += -DDEBUG
endif

