#
# Makefile for the TI network device drivers.
#

obj-$(CONFIG_TI_CPSW) += cpsw-common.o
obj-$(CONFIG_TI_DAVINCI_EMAC) += cpsw-common.o

obj-$(CONFIG_TLAN) += tlan.o
obj-$(CONFIG_CPMAC) += cpmac.o
obj-$(CONFIG_TI_DAVINCI_EMAC) += davinci_emac.o
obj-$(CONFIG_TI_DAVINCI_MDIO) += davinci_mdio.o
obj-$(CONFIG_TI_DAVINCI_CPDMA) += davinci_cpdma.o
obj-$(CONFIG_TI_CPSW_PHY_SEL) += cpsw-phy-sel.o
obj-$(CONFIG_TI_CPSW_ALE) += cpsw_ale.o
obj-$(CONFIG_TI_CPSW) += ti_cpsw.o
ti_cpsw-y := cpsw.o cpts.o

obj-$(CONFIG_TI_KEYSTONE_NETCP_CPTS) += netcp_cpts.o
obj-$(CONFIG_TI_KEYSTONE_NETCP) += keystone_netcp.o
keystone_netcp-y := netcp_core.o
obj-$(CONFIG_TI_KEYSTONE_NETCP_ETHSS) += keystone_netcp_ethss.o
keystone_netcp_ethss-y := netcp_ethss.o netcp_ethss_sysfs.o netcp_sgmii.o \
	$(netcp_cpts-y)
obj-$(CONFIG_TI_KEYSTONE_NETCP_PA_CORE) += netcp_pa_core.o
obj-$(CONFIG_TI_KEYSTONE_NETCP_PA) += keystone_netcp_pa.o
keystone_netcp_pa-y := netcp_pa.o
obj-$(CONFIG_TI_KEYSTONE_NETCP_PA2) += keystone_netcp_pa2.o
keystone_netcp_pa2-y := netcp_pa2.o
obj-$(CONFIG_TI_KEYSTONE_NETCP_QOS) += keystone_netcp_qos.o
keystone_netcp_qos-y := netcp_qos.o
obj-$(CONFIG_TI_KEYSTONE_NETCP_SA) += keystone_netcp_sa.o
keystone_netcp_sa-y := netcp_sa.o

obj-$(CONFIG_TI_PRUETH) += prueth.o
