# mindspore-editdistance-supported-in-cpu
This repository contains codes for supporting editdistance for mindspore in device cpu during Open Source Promotion Plan(OSPP2022). For more information, pleace check out [OSPP website](https://summer-ospp.ac.cn/) as well as the [origin pull request](https://gitee.com/mindspore/mindspore/pulls/40242).

Here are maps between contributed files and their absolute paths in mindspore:
1. edit_distance_cpu.kernel.cc: mindspore/ccsrc/plugin/device/cpu/kernel/edit_distance_cpu_kernel.cc
2. edit_distance_cpu_kernel.h: mindspore/ccsrc/plugin/device/cpu/kernel/edit_distance_cpu_kernel.h
3. edit_distance.cc: mindspore/core/ops/edit_distance.cc
4. array_ops.py: mindspore/python/mindspore/ops/operations/array_ops.py(search 'EditDistance(Primitive)' in this file for relevant details)
