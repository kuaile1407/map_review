# MCU 内存分析报告

生成时间: 2026-06-15 11:28:10

## 1. 内存使用概览

| 内存类型 | 已使用 | 最大值 | 使用率 |
|---------|--------|--------|--------|
| Flash (ROM) | 629.1 KB | 1.0 MB | 61.4% |
| SRAM (RAM) | 219.9 KB | 256.0 KB | 85.9% |

## 2. 详细分布

| 段 | 大小 |
|----|------|
| Code | 537.5 KB |
| RO Data | 85.8 KB |
| RW Data | 5.8 KB |
| ZI Data | 214.1 KB |
| Heap | 32.0 KB |
| Stack | 35.6 KB |

## 3. 段统计 (Top 10)

| 段名 | 大小 |
|------|------|
| text | 515.1 KB |
| noinit | 133.6 KB |
| log_fmt | 125.7 KB |
| rodata | 85.2 KB |
| bss | 77.6 KB |
| hg_log_fmt | 20.1 KB |
| datas | 5.8 KB |
| sw_isr_table | 2.1 KB |
| rom_start | 1.1 KB |
| device_area | 828.0 B |

## 4. 模块统计 (Top 10)

| 模块 | ROM | RAM |
|------|-----|-----|
| vice_controller_s140_debug_hardfp__obfuscated.elf) | 61.6 KB | 4.3 KB |
| app/libapp.a(svc_storage.c.obj) | 15.2 KB | 26.5 KB |
| zephyr/kernel/libkernel.a(mempool.c.obj) | 598.0 B | 32.0 KB |
| tooth/host/libsubsys__bluetooth__host.a(att.c.obj) | 11.0 KB | 15.9 KB |
| ooth/host/libsubsys__bluetooth__host.a(conn.c.obj) | 9.6 KB | 11.9 KB |
| app/libapp.a(svc_ble.c.obj) | 17.7 KB | 281.0 B |
| /host/libsubsys__bluetooth__host.a(hci_core.c.obj) | 12.1 KB | 5.3 KB |
| at/libmpsl.a(libmpsl_debug_hardfp__obfuscated.elf) | 14.3 KB | 1.8 KB |
| zephyr/kernel/libkernel.a(init.c.obj) | 939.0 B | 14.9 KB |
| rt/libsubsys__mgmt__mcumgr__transport.a(smp.c.obj) | 665.0 B | 14.6 KB |
