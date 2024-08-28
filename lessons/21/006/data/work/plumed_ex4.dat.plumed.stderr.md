Stderr for source:  work/plumed_ex4.dat   
Download: [zipped raw stdout](plumed_ex4.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_ex4.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: DUMPPDB ATOMS=cc_data ATOM_INDICES=@nonhydrogens FILE=traj.pdb
Maybe a missing space or a typo?
[fv-az1432-100:05593] *** Process received signal ***
[fv-az1432-100:05593] Signal: Aborted (6)
[fv-az1432-100:05593] Signal code:  (-6)
[fv-az1432-100:05593] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe3ef442520]
[fv-az1432-100:05593] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe3ef4969fc]
[fv-az1432-100:05593] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe3ef442476]
[fv-az1432-100:05593] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe3ef4287f3]
[fv-az1432-100:05593] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe3ef8a2b9e]
[fv-az1432-100:05593] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe3ef8ae20c]
[fv-az1432-100:05593] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe3ef8ae277]
[fv-az1432-100:05593] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe3ef8ae52b]
[fv-az1432-100:05593] [ 8] plumed(+0x12f48)[0x55c465bf2f48]
[fv-az1432-100:05593] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe3ef429d90]
[fv-az1432-100:05593] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe3ef429e40]
[fv-az1432-100:05593] [11] plumed(+0x131e5)[0x55c465bf31e5]
[fv-az1432-100:05593] *** End of error message ***
</pre>
{% endraw %}
