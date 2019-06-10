# ROCm-Solbuild
Trying to create scripts for the packaging of the ROCm modules in Solus,
ROCm - Open Source Platform for HPC and Ultrascale GPU Computing

Build Order:

1) Numactl: Status of building: Package created.

            "lseopkg numactl-2.0.12-1-1-x86_64.eopkg" yields:
                /usr/bin/memhog
                /usr/bin/migratepages
                /usr/bin/migspeed
                /usr/bin/numactl
                /usr/bin/numademo
                /usr/bin/numastat
                /usr/lib64/libnuma.so.1
                /usr/lib64/libnuma.so.1.0.0
                /usr/share/man/man2/move_pages.2
                /usr/share/man/man3/numa.3
                /usr/share/man/man8/migratepages.8
                /usr/share/man/man8/migspeed.8
                /usr/share/man/man8/numactl.8
                /usr/share/man/man8/numastat.8
                
            "lseopkg numactl-devel-2.0.12-1-1-x86_64.eopkg" yields: 
                /usr/include/numa.h
                /usr/include/numacompat1.h
                /usr/include/numaif.h
                /usr/lib64/libnuma.a
                /usr/lib64/libnuma.so
                /usr/lib64/pkgconfig/numa.pc
            
2) Roct:    ROCT-Thunk-Interface
            Status of building: Package created.
         
            "lseopkg ROCT-2.5.0-1-1-x86_64.eopkg" yields: 
                /usr/lib64/libhsakmt.so.1
                /usr/lib64/libhsakmt.so.1.0.6
                
            "lseopkg ROCT-devel-2.5.0-1-1-x86_64.eopkg" yields:
                /usr/include/hsakmt.h
                /usr/include/hsakmttypes.h
                /usr/include/linux/kfd_ioctl.h
                /usr/lib64/libhsakmt.so
                
3) Rocr:    ROCR-Runtime
            Status of building: Package created:
                
            "lseopkg ROCR-2.5.0-1-1-x86_64.eopkg" yields: 
                /usr/lib64/libhsa-runtime64.so.1
                /usr/lib64/libhsa-runtime64.so.1.1.9
                
            "lseopkg ROCR-devel-2.5.0-1-1-x86_64.eopkg" yields:
                /usr/include/hsa/Brig.h
                /usr/include/hsa/amd_hsa_common.h
                /usr/include/hsa/amd_hsa_elf.h
                /usr/include/hsa/amd_hsa_kernel_code.h
                /usr/include/hsa/amd_hsa_queue.h
                /usr/include/hsa/amd_hsa_signal.h
                /usr/include/hsa/hsa.h
                /usr/include/hsa/hsa_api_trace.h
                /usr/include/hsa/hsa_ext_amd.h
                /usr/include/hsa/hsa_ext_finalize.h
                /usr/include/hsa/hsa_ext_image.h
                /usr/include/hsa/hsa_ven_amd_aqlprofile.h
                /usr/include/hsa/hsa_ven_amd_loader.h
                /usr/lib64/libhsa-runtime64.so




         
         
         
