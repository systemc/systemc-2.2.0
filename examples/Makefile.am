## ****************************************************************************
##
##  The following code is derived, directly or indirectly, from the SystemC
##  source code Copyright (c) 1996-2004 by all Contributors.
##  All Rights reserved.
##
##  The contents of this file are subject to the restrictions and limitations
##  set forth in the SystemC Open Source License Version 2.4 (the "License");
##  You may not use this file except in compliance with such restrictions and
##  limitations. You may obtain instructions on how to receive a copy of the
##  License at http://www.systemc.org/. Software distributed by Contributors
##  under the License is distributed on an "AS IS" basis, WITHOUT WARRANTY OF
##  ANY KIND, either express or implied. See the License for the specific
##  language governing rights and limitations under the License.
##
## ****************************************************************************
##
##  examples/Makefile.am --
##  Process this file with automake to produce a Makefile.in file.
##
##  Original Author: Martin Janssen, Synopsys, Inc.
##
## ****************************************************************************
##
##  MODIFICATION LOG - modifiers, enter your name, affiliation and
##  changes you are making here:
##
##  Modifier Name & Affiliation:
##  Description of Modification:
##
## ****************************************************************************

syscexamplesdir = $(prefix)/share/doc/systemc22/examples
syscexamplesfiles = \
	sysc/2.1/dpipe/dpipe.vcproj \
	sysc/2.1/dpipe/main.cpp \
	sysc/2.1/forkjoin/README.txt \
	sysc/2.1/forkjoin/forkjoin.cpp \
	sysc/2.1/forkjoin/forkjoin.vcproj \
	sysc/2.1/reset_signal_is/reset_signal_is.cpp \
	sysc/2.1/reset_signal_is/reset_signal_is.vcproj \
	sysc/2.1/sc_export/README.txt \
	sysc/2.1/sc_export/main.cpp \
	sysc/2.1/sc_export/sc_export.vcproj \
	sysc/2.1/sc_report/README.txt \
	sysc/2.1/sc_report/main.cpp \
	sysc/2.1/sc_report/sc_report.vcproj \
	sysc/2.1/scx_barrier/main.cpp \
	sysc/2.1/scx_barrier/scx_barrier.h \
	sysc/2.1/scx_barrier/scx_barrier.vcproj \
	sysc/2.1/scx_mutex_w_policy/scx_mutex_w_policy.cpp \
	sysc/2.1/scx_mutex_w_policy/scx_mutex_w_policy.vcproj \
	sysc/2.1/specialized_signals/main.cpp \
	sysc/2.1/specialized_signals/scx_signal_int.cpp \
	sysc/2.1/specialized_signals/scx_signal_int.h \
	sysc/2.1/specialized_signals/scx_signal_signed.cpp \
	sysc/2.1/specialized_signals/scx_signal_signed.h \
	sysc/2.1/specialized_signals/scx_signal_uint.cpp \
	sysc/2.1/specialized_signals/scx_signal_uint.h \
	sysc/2.1/specialized_signals/scx_signal_unsigned.cpp \
	sysc/2.1/specialized_signals/scx_signal_unsigned.h \
	sysc/Readme_msvc71.txt \
	sysc/fft/README \
	sysc/fft/fft_flpt/fft.cpp \
	sysc/fft/fft_flpt/fft.h \
	sysc/fft/fft_flpt/fft_flpt.ncb \
	sysc/fft/fft_flpt/fft_flpt.vcproj \
	sysc/fft/fft_flpt/in_imag \
	sysc/fft/fft_flpt/in_imag.1 \
	sysc/fft/fft_flpt/in_imag.2 \
	sysc/fft/fft_flpt/in_imag.3 \
	sysc/fft/fft_flpt/in_imag.4 \
	sysc/fft/fft_flpt/in_real \
	sysc/fft/fft_flpt/in_real.1 \
	sysc/fft/fft_flpt/in_real.2 \
	sysc/fft/fft_flpt/in_real.3 \
	sysc/fft/fft_flpt/in_real.4 \
	sysc/fft/fft_flpt/main.cpp \
	sysc/fft/fft_flpt/out_imag.1.golden \
	sysc/fft/fft_flpt/out_imag.2.golden \
	sysc/fft/fft_flpt/out_imag.3.golden \
	sysc/fft/fft_flpt/out_imag.4.golden \
	sysc/fft/fft_flpt/out_real.1.golden \
	sysc/fft/fft_flpt/out_real.2.golden \
	sysc/fft/fft_flpt/out_real.3.golden \
	sysc/fft/fft_flpt/out_real.4.golden \
	sysc/fft/fft_flpt/sink.cpp \
	sysc/fft/fft_flpt/sink.h \
	sysc/fft/fft_flpt/source.cpp \
	sysc/fft/fft_flpt/source.h \
	sysc/fft/fft_fxpt/fft.cpp \
	sysc/fft/fft_fxpt/fft.h \
	sysc/fft/fft_fxpt/fft_fxpt.vcproj \
	sysc/fft/fft_fxpt/in_imag \
	sysc/fft/fft_fxpt/in_imag.1 \
	sysc/fft/fft_fxpt/in_imag.2 \
	sysc/fft/fft_fxpt/in_imag.3 \
	sysc/fft/fft_fxpt/in_imag.4 \
	sysc/fft/fft_fxpt/in_real \
	sysc/fft/fft_fxpt/in_real.1 \
	sysc/fft/fft_fxpt/in_real.2 \
	sysc/fft/fft_fxpt/in_real.3 \
	sysc/fft/fft_fxpt/in_real.4 \
	sysc/fft/fft_fxpt/main.cpp \
	sysc/fft/fft_fxpt/out_imag.1.golden \
	sysc/fft/fft_fxpt/out_imag.2.golden \
	sysc/fft/fft_fxpt/out_imag.3.golden \
	sysc/fft/fft_fxpt/out_imag.4.golden \
	sysc/fft/fft_fxpt/out_real.1.golden \
	sysc/fft/fft_fxpt/out_real.2.golden \
	sysc/fft/fft_fxpt/out_real.3.golden \
	sysc/fft/fft_fxpt/out_real.4.golden \
	sysc/fft/fft_fxpt/sink.cpp \
	sysc/fft/fft_fxpt/sink.h \
	sysc/fft/fft_fxpt/source.cpp \
	sysc/fft/fft_fxpt/source.h \
	sysc/fir/README \
	sysc/fir/display.cpp \
	sysc/fir/display.h \
	sysc/fir/fir.cpp \
	sysc/fir/fir.h \
	sysc/fir/fir.vcproj \
	sysc/fir/fir_const.h \
	sysc/fir/fir_data.cpp \
	sysc/fir/fir_data.h \
	sysc/fir/fir_fsm.cpp \
	sysc/fir/fir_fsm.h \
	sysc/fir/fir_top.h \
	sysc/fir/log \
	sysc/fir/main.cpp \
	sysc/fir/main_rtl.cpp \
	sysc/fir/rtl_log \
	sysc/fir/stimulus.cpp \
	sysc/fir/stimulus.h \
	sysc/pipe/README \
	sysc/pipe/display.cpp \
	sysc/pipe/display.h \
	sysc/pipe/golden.log \
	sysc/pipe/main.cpp \
	sysc/pipe/numgen.cpp \
	sysc/pipe/numgen.h \
	sysc/pipe/pipe.vcproj \
	sysc/pipe/stage1.cpp \
	sysc/pipe/stage1.h \
	sysc/pipe/stage2.cpp \
	sysc/pipe/stage2.h \
	sysc/pipe/stage3.cpp \
	sysc/pipe/stage3.h \
	sysc/pkt_switch/README \
	sysc/pkt_switch/fifo.cpp \
	sysc/pkt_switch/fifo.h \
	sysc/pkt_switch/main.cpp \
	sysc/pkt_switch/pkt.h \
	sysc/pkt_switch/pkt_switch.vcproj \
	sysc/pkt_switch/receiver.cpp \
	sysc/pkt_switch/receiver.h \
	sysc/pkt_switch/sender.cpp \
	sysc/pkt_switch/sender.h \
	sysc/pkt_switch/switch.cpp \
	sysc/pkt_switch/switch.h \
	sysc/pkt_switch/switch_clk.cpp \
	sysc/pkt_switch/switch_clk.h \
	sysc/pkt_switch/switch_reg.h \
	sysc/risc_cpu/README \
	sysc/risc_cpu/README_TYPESCRIPT \
	sysc/risc_cpu/abc.asm \
	sysc/risc_cpu/assembler.pl \
	sysc/risc_cpu/bios \
	sysc/risc_cpu/bios.cpp \
	sysc/risc_cpu/bios.h \
	sysc/risc_cpu/dcache \
	sysc/risc_cpu/dcache.cpp \
	sysc/risc_cpu/dcache.h \
	sysc/risc_cpu/decode.cpp \
	sysc/risc_cpu/decode.h \
	sysc/risc_cpu/directive.h \
	sysc/risc_cpu/exec.cpp \
	sysc/risc_cpu/exec.h \
	sysc/risc_cpu/fetch.cpp \
	sysc/risc_cpu/fetch.h \
	sysc/risc_cpu/floating.cpp \
	sysc/risc_cpu/floating.h \
	sysc/risc_cpu/icache \
	sysc/risc_cpu/icache.cpp \
	sysc/risc_cpu/icache.h \
	sysc/risc_cpu/main.cpp \
	sysc/risc_cpu/mmxu.cpp \
	sysc/risc_cpu/mmxu.h \
	sysc/risc_cpu/paging.cpp \
	sysc/risc_cpu/paging.h \
	sysc/risc_cpu/pic.cpp \
	sysc/risc_cpu/pic.h \
	sysc/risc_cpu/printout \
	sysc/risc_cpu/program \
	sysc/risc_cpu/register \
	sysc/risc_cpu/risc_cpu.vcproj \
	sysc/risc_cpu/test.asm \
	sysc/risc_cpu/test1.asm \
	sysc/rsa/README \
	sysc/rsa/rsa.cpp \
	sysc/rsa/rsa.vcproj \
	sysc/simple_bus/.DS_Store \
	sysc/simple_bus/ChangeLog \
	sysc/simple_bus/LEGAL \
	sysc/simple_bus/README \
	sysc/simple_bus/SLIDES.pdf \
	sysc/simple_bus/simple_bus.cpp \
	sysc/simple_bus/simple_bus.golden \
	sysc/simple_bus/simple_bus.h \
	sysc/simple_bus/simple_bus.vcproj \
	sysc/simple_bus/simple_bus_arbiter.cpp \
	sysc/simple_bus/simple_bus_arbiter.h \
	sysc/simple_bus/simple_bus_arbiter_if.h \
	sysc/simple_bus/simple_bus_blocking_if.h \
	sysc/simple_bus/simple_bus_direct_if.h \
	sysc/simple_bus/simple_bus_fast_mem.h \
	sysc/simple_bus/simple_bus_main.cpp \
	sysc/simple_bus/simple_bus_master_blocking.cpp \
	sysc/simple_bus/simple_bus_master_blocking.h \
	sysc/simple_bus/simple_bus_master_direct.cpp \
	sysc/simple_bus/simple_bus_master_direct.h \
	sysc/simple_bus/simple_bus_master_non_blocking.cpp \
	sysc/simple_bus/simple_bus_master_non_blocking.h \
	sysc/simple_bus/simple_bus_non_blocking_if.h \
	sysc/simple_bus/simple_bus_request.h \
	sysc/simple_bus/simple_bus_slave_if.h \
	sysc/simple_bus/simple_bus_slow_mem.h \
	sysc/simple_bus/simple_bus_test.h \
	sysc/simple_bus/simple_bus_tools.cpp \
	sysc/simple_bus/simple_bus_types.cpp \
	sysc/simple_bus/simple_bus_types.h \
	sysc/simple_fifo/simple_fifo.cpp \
	sysc/simple_fifo/simple_fifo.vcproj \
	sysc/simple_perf/simple_perf.cpp \
	sysc/simple_perf/simple_perf.vcproj

install-data-local:
	@for f in $(syscexamplesfiles); do \
## Compute the install directory at runtime.
	  d=`echo $$f | sed -e s,/[^/]*$$,,`; \
## Make the install directory.
	  $(mkinstalldirs) $(DESTDIR)$(syscexamplesdir)/$$d; \
## Actually install the file.
	  $(INSTALL_DATA) $$f $(DESTDIR)$(syscexamplesdir)/$$f; \
	done

uninstall-local:
	@$(NORMAL_UNINSTALL)
	-rmdir $(syscexamplesdir)

## Taf!
