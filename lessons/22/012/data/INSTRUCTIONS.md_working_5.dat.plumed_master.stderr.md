Stderr for source:  INSTRUCTIONS.md_working_5.dat   
Download: [zipped raw stdout](INSTRUCTIONS.md_working_5.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](INSTRUCTIONS.md_working_5.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action MATHEVAL with label @s133 : cannot find action named cv (hint! the actions with value in this ActionSet are: timestep kBT posx posy posz Masses Charges Box driver q6_mat q6_sh q6_denom_ones q6_denom q6_sp q6_rmn-n6 q6_imn-n6 q6_rmn-n5 q6_imn-n5 q6_rmn-n4 q6_imn-n4 q6_rmn-n3 q6_imn-n3 q6_rmn-n2 q6_imn-n2 q6_rmn-n1 q6_imn-n1 q6_rmn-0 q6_imn-0 q6_rmn-p1 q6_imn-p1 q6_rmn-p2 q6_imn-p2 q6_rmn-p3 q6_imn-p3 q6_rmn-p4 q6_imn-p4 q6_rmn-p5 q6_imn-p5 q6_rmn-p6 q6_imn-p6 q6_rms-n6 q6_ims-n6 q6_rms-n5 q6_ims-n5 q6_rms-n4 q6_ims-n4 q6_rms-n3 q6_ims-n3 q6_rms-n2 q6_ims-n2 q6_rms-n1 q6_ims-n1 q6_rms-0 q6_ims-0 q6_rms-p1 q6_ims-p1 q6_rms-p2 q6_ims-p2 q6_rms-p3 q6_ims-p3 q6_rms-p4 q6_ims-p4 q6_rms-p5 q6_ims-p5 q6_rms-p6 q6_ims-p6 q6_vmean2 q6_vmean q6_norm2 q6_norm q6 )
[fv-az1427-785:08955] *** Process received signal ***
[fv-az1427-785:08955] Signal: Aborted (6)
[fv-az1427-785:08955] Signal code:  (-6)
[fv-az1427-785:08955] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f079b642520]
[fv-az1427-785:08955] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f079b6969fc]
[fv-az1427-785:08955] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f079b642476]
[fv-az1427-785:08955] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f079b6287f3]
[fv-az1427-785:08955] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f079baa2b9e]
[fv-az1427-785:08955] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f079baae20c]
[fv-az1427-785:08955] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f079baae277]
[fv-az1427-785:08955] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f079baae52b]
[fv-az1427-785:08955] [ 8] plumed_master(+0x14274)[0x556b5a112274]
[fv-az1427-785:08955] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f079b629d90]
[fv-az1427-785:08955] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f079b629e40]
[fv-az1427-785:08955] [11] plumed_master(+0x14ed5)[0x556b5a112ed5]
[fv-az1427-785:08955] *** End of error message ***
</pre>
{% endraw %}
