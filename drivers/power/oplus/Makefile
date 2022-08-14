oplus_chg-y	+= gauge_ic/
oplus_chg-y	+= vooc_ic/
oplus_chg-y	+= adapter_ic/
oplus_chg-y	+= charger_ic/
oplus_chg-y	+= oplus_charger.o
oplus_chg-y	+= oplus_gauge.o
oplus_chg-y	+= oplus_vooc.o
oplus_chg-y	+= oplus_adapter.o
oplus_chg-y	+= oplus_wireless.o
oplus_chg-y	+= oplus_short.o
oplus_chg-y	+= oplus_debug_info.o
oplus_chg-y	+= oplus_configfs.o
obj-$(CONFIG_OPLUS_CHG) := oplus_chg.o

ifeq ($(CONFIG_OPLUS_SM4350R_CHARGER),y)
	obj-$(CONFIG_OPLUS_BQ25601D_SLAVE_CHARGER)	+= oplus_bq25600_slave.o
endif
