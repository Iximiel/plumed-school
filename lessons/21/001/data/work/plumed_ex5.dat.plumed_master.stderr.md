Stderr for source:  work/plumed_ex5.dat   
Download: [zipped raw stdout](plumed_ex5.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_ex5.dat.plumed_master.stderr.txt.zip) 
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
[fv-az1427-785:09956] *** Process received signal ***
[fv-az1427-785:09956] Signal: Aborted (6)
[fv-az1427-785:09956] Signal code:  (-6)
[fv-az1427-785:09956] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbf2c642520]
[fv-az1427-785:09956] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbf2c6969fc]
[fv-az1427-785:09956] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbf2c642476]
[fv-az1427-785:09956] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbf2c6287f3]
[fv-az1427-785:09956] [ 4] /lib/x86_64-linux-gnu/libfabric.so.1(+0x76b4e)[0x7fbf15360b4e]
[fv-az1427-785:09956] [ 5] /lib/x86_64-linux-gnu/libc.so.6(+0xeaf48)[0x7fbf2c6eaf48]
[fv-az1427-785:09956] [ 6] /lib/x86_64-linux-gnu/libc.so.6(__libc_fork+0x71)[0x7fbf2c6ea711]
[fv-az1427-785:09956] [ 7] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10SubprocessC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xc1)[0x7fbf2dd60ff1]
[fv-az1427-785:09956] [ 8] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14GenericMolInfo15interpretSymbolERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEERSt6vectorINS_10AtomNumberESaISA_EE+0x162b)[0x7fbf2d64547b]
[fv-az1427-785:09956] [ 9] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD15ActionAtomistic17interpretAtomListERSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKS1_IPNS_5ValueESaISC_EEPNS_6ActionERS1_INS_10AtomNumberESaISJ_EE+0x6c1)[0x7fbf2d5cda71]
[fv-az1427-785:09956] [10] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD15ActionAtomistic13parseAtomListERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEiRSt6vectorINS_10AtomNumberESaISA_EE+0x10d)[0x7fbf2d5cefed]
[fv-az1427-785:09956] [11] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD7generic14WholeMoleculesC1ERKNS_13ActionOptionsE+0x251)[0x7fbf2d848bd1]
[fv-az1427-785:09956] [12] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD18ActionRegistrationINS_7generic14WholeMoleculesEE6createERKNS_13ActionOptionsE+0x27)[0x7fbf2d84b277]
[fv-az1427-785:09956] [13] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x383)[0x7fbf2d5d2253]
[fv-az1427-785:09956] [14] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x2da)[0x7fbf2d658a0a]
[fv-az1427-785:09956] [15] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5c)[0x7fbf2d6591bc]
[fv-az1427-785:09956] [16] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9f)[0x7fbf2d65e8cf]
[fv-az1427-785:09956] [17] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain4initEv+0xb6a)[0x7fbf2d65f4aa]
[fv-az1427-785:09956] [18] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x29bf)[0x7fbf2d66244f]
[fv-az1427-785:09956] [19] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x2b2a)[0x7fbf2d34ebba]
[fv-az1427-785:09956] [20] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x7d2)[0x7fbf2d614912]
[fv-az1427-785:09956] [21] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x53e)[0x7fbf2d61737e]
[fv-az1427-785:09956] [22] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x12d4)[0x7fbf2d660d64]
[fv-az1427-785:09956] [23] /home/runner/opt/lib/libplumed_masterKernel.so(+0x86a441)[0x7fbf2d66a441]
[fv-az1427-785:09956] [24] plumed_master(+0x1e207)[0x55f59d8ea207]
[fv-az1427-785:09956] [25] plumed_master(+0x14d61)[0x55f59d8e0d61]
[fv-az1427-785:09956] [26] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbf2c629d90]
[fv-az1427-785:09956] [27] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbf2c629e40]
[fv-az1427-785:09956] [28] plumed_master(+0x14ed5)[0x55f59d8e0ed5]
[fv-az1427-785:09956] *** End of error message ***
</pre>
{% endraw %}
