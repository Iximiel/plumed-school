Stderr for source:  work/plumed_ex3.dat   
Download: [zipped raw stdout](plumed_ex3.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_ex3.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action LANDMARK_SELECT_FPS with label fps : input analysis action was not specified use USE_OUTPUT_DATA_FROM
[fv-az1432-100:05562] *** Process received signal ***
[fv-az1432-100:05562] Signal: Aborted (6)
[fv-az1432-100:05562] Signal code:  (-6)
[fv-az1432-100:05562] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0c2c442520]
[fv-az1432-100:05562] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0c2c4969fc]
[fv-az1432-100:05562] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0c2c442476]
[fv-az1432-100:05562] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0c2c4287f3]
[fv-az1432-100:05562] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0c2c8a2b9e]
[fv-az1432-100:05562] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0c2c8ae20c]
[fv-az1432-100:05562] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0c2c8ae277]
[fv-az1432-100:05562] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0c2c8ae52b]
[fv-az1432-100:05562] [ 8] plumed(+0x12f48)[0x560466d8af48]
[fv-az1432-100:05562] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0c2c429d90]
[fv-az1432-100:05562] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0c2c429e40]
[fv-az1432-100:05562] [11] plumed(+0x131e5)[0x560466d8b1e5]
[fv-az1432-100:05562] *** End of error message ***
</pre>
{% endraw %}
