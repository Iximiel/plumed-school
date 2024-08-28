Stderr for source:  INSTRUCTIONS.md_working_6.dat   
Download: [zipped raw stdout](INSTRUCTIONS.md_working_6.dat.plumed.stdout.txt.zip) - [zipped raw stderr](INSTRUCTIONS.md_working_6.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action UPPER_WALLS with label uwall : cannot find action named cv (hint! the actions with value in this ActionSet are: )
[fv-az1427-785:08978] *** Process received signal ***
[fv-az1427-785:08978] Signal: Aborted (6)
[fv-az1427-785:08978] Signal code:  (-6)
[fv-az1427-785:08978] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0898242520]
[fv-az1427-785:08978] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f08982969fc]
[fv-az1427-785:08978] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0898242476]
[fv-az1427-785:08978] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f08982287f3]
[fv-az1427-785:08978] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f08986a2b9e]
[fv-az1427-785:08978] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f08986ae20c]
[fv-az1427-785:08978] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f08986ae277]
[fv-az1427-785:08978] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f08986ae52b]
[fv-az1427-785:08978] [ 8] plumed(+0x12f48)[0x5616f3a06f48]
[fv-az1427-785:08978] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0898229d90]
[fv-az1427-785:08978] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0898229e40]
[fv-az1427-785:08978] [11] plumed(+0x131e5)[0x5616f3a071e5]
[fv-az1427-785:08978] *** End of error message ***
</pre>
{% endraw %}
