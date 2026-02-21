# MCU 内存分析报告

生成时间: 2026-02-21 06:08:16

## 1. 内存使用概览

| 内存类型 | 已使用 | 最大值 | 使用率 |
|---------|--------|--------|--------|
| Flash (ROM) | 367.2 KB | 1.0 MB | 35.9% |
| SRAM (RAM) | 139.4 KB | 256.0 KB | 54.4% |

## 2. 详细分布

| 段 | 大小 |
|----|------|
| Code | 316.6 KB |
| RO Data | 45.7 KB |
| RW Data | 4.9 KB |
| ZI Data | 134.4 KB |
| Heap | 32.0 KB |
| Stack | 24.6 KB |

## 3. 段统计 (Top 10)

| 段名 | 大小 |
|------|------|
| text | 314.5 KB |
| noinit | 89.5 KB |
| rodata | 45.1 KB |
| bss | 42.4 KB |
| datas | 4.9 KB |
| sw_isr_table | 2.1 KB |
| rom_start | 1.1 KB |
| device_area | 720.0 B |
| log_const_area | 584.0 B |
| initlevel | 328.0 B |

## 4. 模块统计 (Top 10)

| 模块 | ROM | RAM |
|------|-----|-----|
| vice_controller_s140_debug_hardfp__obfuscated.elf) | 59.9 KB | 4.3 KB |
| zephyr/kernel/libkernel.a(mempool.c.obj) | 574.0 B | 32.0 KB |
| modules/littlefs/libmodules__littlefs.a(lfs.c.obj) | 24.7 KB | 0.0 B |
| app/libapp.a(svc_storage.c.obj) | 1.3 KB | 17.3 KB |
| /host/libsubsys__bluetooth__host.a(hci_core.c.obj) | 13.2 KB | 5.3 KB |
| at/libmpsl.a(libmpsl_debug_hardfp__obfuscated.elf) | 14.3 KB | 1.8 KB |
| rt/libsubsys__mgmt__mcumgr__transport.a(smp.c.obj) | 665.0 B | 14.6 KB |
| tooth/host/libsubsys__bluetooth__host.a(att.c.obj) | 10.8 KB | 3.6 KB |
| ooth/host/libsubsys__bluetooth__host.a(gatt.c.obj) | 12.4 KB | 658.0 B |
| zephyr/kernel/libkernel.a(init.c.obj) | 926.0 B | 10.8 KB |
