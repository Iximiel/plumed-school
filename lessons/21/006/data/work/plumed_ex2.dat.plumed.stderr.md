Stderr for source:  work/plumed_ex2.dat   
Download: [zipped raw stdout](plumed_ex2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_ex2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action PCA with label pca : action cc has no component named cc (hint! the components in this actions are: )
[fv-az1432-100:05524] *** Process received signal ***
[fv-az1432-100:05524] Signal: Aborted (6)
[fv-az1432-100:05524] Signal code:  (-6)
[fv-az1432-100:05524] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7711642520]
[fv-az1432-100:05524] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f77116969fc]
[fv-az1432-100:05524] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7711642476]
[fv-az1432-100:05524] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f77116287f3]
[fv-az1432-100:05524] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7711aa2b9e]
[fv-az1432-100:05524] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7711aae20c]
[fv-az1432-100:05524] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7711aae277]
[fv-az1432-100:05524] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7711aae52b]
[fv-az1432-100:05524] [ 8] plumed(+0x12f48)[0x563d52d43f48]
[fv-az1432-100:05524] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7711629d90]
[fv-az1432-100:05524] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7711629e40]
[fv-az1432-100:05524] [11] plumed(+0x131e5)[0x563d52d441e5]
[fv-az1432-100:05524] *** End of error message ***
</pre>
{% endraw %}
