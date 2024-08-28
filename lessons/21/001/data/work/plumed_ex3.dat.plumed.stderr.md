Stderr for source:  work/plumed_ex3.dat   
Download: [zipped raw stdout](plumed_ex3.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_ex3.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
A process has executed an operation involving a call
to the fork() system call to create a child process.

As a result, the libfabric EFA provider is operating in
a condition that could result in memory corruption or
other system errors.

For the libfabric EFA provider to work safely when fork()
is called, you will need to set the following environment
variable:
RDMAV_FORK_SAFE

However, setting this environment variable can result in
signficant performance impact to your application due to
increased cost of memory registration.

You may want to check with your application vendor to see
if an application-level alternative (of not using fork)
exists.

Your job will now abort.
[fv-az1427-785:09888] *** Process received signal ***
[fv-az1427-785:09888] Signal: Aborted (6)
[fv-az1427-785:09888] Signal code:  (-6)
[fv-az1427-785:09888] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f92e4642520]
[fv-az1427-785:09888] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f92e46969fc]
[fv-az1427-785:09888] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f92e4642476]
[fv-az1427-785:09888] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f92e46287f3]
[fv-az1427-785:09888] [ 4] /lib/x86_64-linux-gnu/libfabric.so.1(+0x76b4e)[0x7f92cd356b4e]
[fv-az1427-785:09888] [ 5] /lib/x86_64-linux-gnu/libc.so.6(+0xeaf48)[0x7f92e46eaf48]
[fv-az1427-785:09888] [ 6] /lib/x86_64-linux-gnu/libc.so.6(__libc_fork+0x71)[0x7f92e46ea711]
[fv-az1427-785:09888] [ 7] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10SubprocessC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xbc)[0x7f92e59a4f5c]
[fv-az1427-785:09888] [ 8] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14GenericMolInfo15interpretSymbolERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEERSt6vectorINS_10AtomNumberESaISA_EE+0x163c)[0x7f92e549d71c]
[fv-az1427-785:09888] [ 9] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD15ActionAtomistic17interpretAtomListERSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERS1_INS_10AtomNumberESaISB_EE+0x547)[0x7f92e545adb7]
[fv-az1427-785:09888] [10] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD15ActionAtomistic13parseAtomListERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEiRSt6vectorINS_10AtomNumberESaISA_EE+0xf1)[0x7f92e545b561]
[fv-az1427-785:09888] [11] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD6colvar8GyrationC1ERKNS_13ActionOptionsE+0xf1)[0x7f92e5423901]
[fv-az1427-785:09888] [12] /home/runner/opt/lib/libplumedKernel.so(+0x624007)[0x7f92e5424007]
[fv-az1427-785:09888] [13] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKNS_13ActionOptionsE+0x5fc)[0x7f92e5460f6c]
[fv-az1427-785:09888] [14] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EE+0x288)[0x7f92e54b6098]
[fv-az1427-785:09888] [15] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x54)[0x7f92e54b6534]
[fv-az1427-785:09888] [16] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xa6)[0x7f92e54b8d06]
[fv-az1427-785:09888] [17] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x13ba)[0x7f92e54ba29a]
[fv-az1427-785:09888] [18] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEERKNS_11TypesafePtrE+0x2566)[0x7f92e54bcda6]
[fv-az1427-785:09888] [19] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x314e)[0x7f92e5245fae]
[fv-az1427-785:09888] [20] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x7d3)[0x7f92e547b8a3]
[fv-az1427-785:09888] [21] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3cmdERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEERKNS_11TypesafePtrE+0x67e)[0x7f92e547e4de]
[fv-az1427-785:09888] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEERKNS_11TypesafePtrE+0x208d)[0x7f92e54bc8cd]
[fv-az1427-785:09888] [23] /home/runner/opt/lib/libplumedKernel.so(+0x6c2e05)[0x7f92e54c2e05]
[fv-az1427-785:09888] [24] plumed(+0x1a6f0)[0x559820ec96f0]
[fv-az1427-785:09888] [25] plumed(+0x1364e)[0x559820ec264e]
[fv-az1427-785:09888] [26] plumed(+0x1311c)[0x559820ec211c]
[fv-az1427-785:09888] [27] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f92e4629d90]
[fv-az1427-785:09888] [28] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f92e4629e40]
[fv-az1427-785:09888] [29] plumed(+0x131e5)[0x559820ec21e5]
[fv-az1427-785:09888] *** End of error message ***
</pre>
{% endraw %}
