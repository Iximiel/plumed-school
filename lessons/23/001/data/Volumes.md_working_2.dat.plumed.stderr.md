Stderr for source:  Volumes.md_working_2.dat   
Download: [zipped raw stdout](Volumes.md_working_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](Volumes.md_working_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action INSPHERE with label sp : keyword DATA is compulsory for this action
[fv-az1427-785:07325] *** Process received signal ***
[fv-az1427-785:07325] Signal: Aborted (6)
[fv-az1427-785:07325] Signal code:  (-6)
[fv-az1427-785:07325] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff09ca42520]
[fv-az1427-785:07325] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff09ca969fc]
[fv-az1427-785:07325] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff09ca42476]
[fv-az1427-785:07325] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff09ca287f3]
[fv-az1427-785:07325] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff09cea2b9e]
[fv-az1427-785:07325] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff09ceae20c]
[fv-az1427-785:07325] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff09ceae277]
[fv-az1427-785:07325] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff09ceae52b]
[fv-az1427-785:07325] [ 8] plumed(+0x12f48)[0x556ad89f6f48]
[fv-az1427-785:07325] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff09ca29d90]
[fv-az1427-785:07325] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff09ca29e40]
[fv-az1427-785:07325] [11] plumed(+0x131e5)[0x556ad89f71e5]
[fv-az1427-785:07325] *** End of error message ***
</pre>
{% endraw %}
