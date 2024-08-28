Stderr for source:  INSTRUCTIONS.md_working_7.dat   
Download: [zipped raw stdout](INSTRUCTIONS.md_working_7.dat.plumed.stdout.txt.zip) - [zipped raw stderr](INSTRUCTIONS.md_working_7.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action OPES_METAD with label opes : cannot find action named cv (hint! the actions with value in this ActionSet are: )
[fv-az1427-785:09011] *** Process received signal ***
[fv-az1427-785:09011] Signal: Aborted (6)
[fv-az1427-785:09011] Signal code:  (-6)
[fv-az1427-785:09011] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1d89642520]
[fv-az1427-785:09011] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1d896969fc]
[fv-az1427-785:09011] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1d89642476]
[fv-az1427-785:09011] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1d896287f3]
[fv-az1427-785:09011] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1d89aa2b9e]
[fv-az1427-785:09011] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1d89aae20c]
[fv-az1427-785:09011] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1d89aae277]
[fv-az1427-785:09011] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1d89aae52b]
[fv-az1427-785:09011] [ 8] plumed(+0x12f48)[0x559ddb653f48]
[fv-az1427-785:09011] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1d89629d90]
[fv-az1427-785:09011] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1d89629e40]
[fv-az1427-785:09011] [11] plumed(+0x131e5)[0x559ddb6541e5]
[fv-az1427-785:09011] *** End of error message ***
</pre>
{% endraw %}
