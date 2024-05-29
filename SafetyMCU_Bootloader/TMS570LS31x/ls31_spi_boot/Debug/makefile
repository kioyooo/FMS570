################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := D:/CCS12.7.0.00007_win64/ccs/tools/compiler/ti-cgt-arm_20.2.7.LTS

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./Fapi_UserDefinedFunctions.obj" \
"./bl_check.obj" \
"./bl_dcan.obj" \
"./bl_flash.obj" \
"./bl_led_demo.obj" \
"./bl_main.obj" \
"./bl_spi.obj" \
"./bl_spi_packet.obj" \
"./bl_uart.obj" \
"./bl_ymodem.obj" \
"./hw_dcan.obj" \
"./hw_esm.obj" \
"./hw_gio.obj" \
"./hw_pinmux.obj" \
"./hw_sci.obj" \
"./hw_spi.obj" \
"./notification.obj" \
"./sci_common.obj" \
"./sw_hw_ver.obj" \
"./sys_core.obj" \
"./sys_intvecs.obj" \
"./sys_phantom.obj" \
"./sys_startup.obj" \
"./system.obj" \
"./ymodem_crc16.obj" \
"C:/Users/user/Documents/WeChat Files/wxid_sc6x6uvybbc212/FileStorage/File/2024-05/spna199/SafetyMCU_Bootloader/TMS570LS31x/bl_link.cmd" \
$(GEN_CMDS__FLAG) \
-l"C:/Users/user/Documents/WeChat Files/wxid_sc6x6uvybbc212/FileStorage/File/2024-05/spna199/SafetyMCU_Bootloader/lib/F021_API_CortexR4_BE.lib" \
-lrtsv7R4_T_be_eabi.lib \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
ls31_spi_boot.out 

EXE_OUTPUTS__QUOTED += \
"ls31_spi_boot.out" 


# All Target
all: ls31_spi_boot.out

# Tool invocations
ls31_spi_boot.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: "$@"'
	@echo '正在调用： ARM Linker'
	"D:/CCS12.7.0.00007_win64/ccs/tools/compiler/ti-cgt-arm_20.2.7.LTS/bin/armcl" -mv7R4 --code_state=32 --abi=eabi -g --diag_warning=225 --diag_wrap=off --display_error_number --enum_type=packed -z -m"ls31_spi_boot.map" --stack_size=0x800 --heap_size=0x800 -i"D:/CCS12.7.0.00007_win64/ccs/tools/compiler/ti-cgt-arm_20.2.7.LTS/lib" -i"D:/CCS12.7.0.00007_win64/ccs/tools/compiler/ti-cgt-arm_20.2.7.LTS/include" --reread_libs --diag_wrap=off --display_error_number --warn_sections --xml_link_info="ls31_spi_boot_linkInfo.xml" --rom_model --be32 -o "ls31_spi_boot.out" $(ORDERED_OBJS)
	@echo 'Finished building target: "$@"'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(EXE_OUTPUTS__QUOTED)
	-$(RM) "Fapi_UserDefinedFunctions.obj" "bl_check.obj" "bl_dcan.obj" "bl_flash.obj" "bl_led_demo.obj" "bl_main.obj" "bl_spi.obj" "bl_spi_packet.obj" "bl_uart.obj" "bl_ymodem.obj" "hw_dcan.obj" "hw_esm.obj" "hw_gio.obj" "hw_pinmux.obj" "hw_sci.obj" "hw_spi.obj" "notification.obj" "sci_common.obj" "sw_hw_ver.obj" "sys_core.obj" "sys_intvecs.obj" "sys_phantom.obj" "sys_startup.obj" "system.obj" "ymodem_crc16.obj" 
	-$(RM) "Fapi_UserDefinedFunctions.d" "bl_check.d" "bl_dcan.d" "bl_flash.d" "bl_led_demo.d" "bl_main.d" "bl_spi.d" "bl_spi_packet.d" "bl_uart.d" "bl_ymodem.d" "hw_dcan.d" "hw_esm.d" "hw_gio.d" "hw_pinmux.d" "hw_sci.d" "hw_spi.d" "notification.d" "sci_common.d" "sw_hw_ver.d" "sys_phantom.d" "sys_startup.d" "system.d" 
	-$(RM) "sys_core.d" "sys_intvecs.d" "ymodem_crc16.d" 
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

