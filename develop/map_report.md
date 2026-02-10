# MCU 内存分析报告

生成时间: 2026-02-10 19:36:18

## 1. 内存使用概览

| 内存类型 | 已使用 | 最大值 | 使用率 |
|---------|--------|--------|--------|
| Flash (ROM) | 468.3 KB | 1.0 MB | 45.7% |
| SRAM (RAM) | 143.3 KB | 256.0 KB | 56.0% |

## 2. 详细分布

| 段 | 大小 |
|----|------|
| Code | 396.0 KB |
| RO Data | 68.2 KB |
| RW Data | 4.1 KB |
| ZI Data | 139.2 KB |
| Heap | 32.0 KB |
| Stack | 24.6 KB |

## 3. 段统计 (Top 10)

| 段名 | 大小 |
|------|------|
| text | 393.8 KB |
| noinit | 92.3 KB |
| rodata | 67.6 KB |
| bss | 44.0 KB |
| datas | 4.1 KB |
| sw_isr_table | 2.1 KB |
| rom_start | 1.1 KB |
| log_const_area | 712.0 B |
| device_area | 684.0 B |
| initlevel | 328.0 B |

## 4. 模块统计 (Top 10)

| 模块 | ROM | RAM |
|------|-----|-----|
| vice_controller_s140_debug_hardfp__obfuscated.elf) | 61.6 KB | 4.3 KB |
| zephyr/kernel/libkernel.a(mempool.c.obj) | 598.0 B | 32.0 KB |
| modules/littlefs/libmodules__littlefs.a(lfs.c.obj) | 24.7 KB | 0.0 B |
| /host/libsubsys__bluetooth__host.a(hci_core.c.obj) | 14.5 KB | 5.3 KB |
| app/libapp.a(svc_storage.c.obj) | 1.3 KB | 17.3 KB |
| at/libmpsl.a(libmpsl_debug_hardfp__obfuscated.elf) | 14.3 KB | 1.8 KB |
| rt/libsubsys__mgmt__mcumgr__transport.a(smp.c.obj) | 665.0 B | 14.6 KB |
| tooth/host/libsubsys__bluetooth__host.a(att.c.obj) | 11.0 KB | 3.6 KB |
| ooth/host/libsubsys__bluetooth__host.a(gatt.c.obj) | 11.7 KB | 306.0 B |
| zephyr/kernel/libkernel.a(init.c.obj) | 926.0 B | 10.8 KB |
