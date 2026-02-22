# MCU 内存分析报告

生成时间: 2026-02-22 16:35:55

## 1. 内存使用概览

| 内存类型 | 已使用 | 最大值 | 使用率 |
|---------|--------|--------|--------|
| Flash (ROM) | 524.8 KB | 1.0 MB | 51.3% |
| SRAM (RAM) | 145.0 KB | 256.0 KB | 56.7% |

## 2. 详细分布

| 段 | 大小 |
|----|------|
| Code | 442.7 KB |
| RO Data | 77.9 KB |
| RW Data | 4.3 KB |
| ZI Data | 140.7 KB |
| Heap | 32.0 KB |
| Stack | 24.6 KB |

## 3. 段统计 (Top 10)

| 段名 | 大小 |
|------|------|
| text | 440.5 KB |
| noinit | 92.5 KB |
| rodata | 77.1 KB |
| bss | 45.3 KB |
| datas | 4.3 KB |
| sw_isr_table | 2.1 KB |
| rom_start | 1.1 KB |
| log_const_area | 752.0 B |
| device_area | 720.0 B |
| initlevel | 336.0 B |

## 4. 模块统计 (Top 10)

| 模块 | ROM | RAM |
|------|-----|-----|
| vice_controller_s140_debug_hardfp__obfuscated.elf) | 61.6 KB | 4.3 KB |
| zephyr/kernel/libkernel.a(mempool.c.obj) | 598.0 B | 32.0 KB |
| modules/littlefs/libmodules__littlefs.a(lfs.c.obj) | 24.7 KB | 0.0 B |
| c__uarp__UARPDK.a(CoreUARPPlatformAccessory.c.obj) | 21.3 KB | 0.0 B |
| /host/libsubsys__bluetooth__host.a(hci_core.c.obj) | 14.5 KB | 5.3 KB |
| app/libapp.a(svc_storage.c.obj) | 1.3 KB | 17.3 KB |
| at/libmpsl.a(libmpsl_debug_hardfp__obfuscated.elf) | 14.3 KB | 1.8 KB |
| rt/libsubsys__mgmt__mcumgr__transport.a(smp.c.obj) | 665.0 B | 14.6 KB |
| tooth/host/libsubsys__bluetooth__host.a(att.c.obj) | 11.0 KB | 3.6 KB |
| tooth/host/libsubsys__bluetooth__host.a(smp.c.obj) | 12.8 KB | 796.0 B |
