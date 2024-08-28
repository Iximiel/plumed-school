Stderr for source:  INSTRUCTIONS.md_working_1.dat   
Download: [zipped raw stdout](INSTRUCTIONS.md_working_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](INSTRUCTIONS.md_working_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(pytorch/PytorchModel.cpp:139) PLMD::function::pytorch::PytorchModel::PytorchModel(const PLMD::ActionOptions&)
The FILE: 'torch_model.ptc' does not exist.
[fv-az1432-100:05460] *** Process received signal ***
[fv-az1432-100:05460] Signal: Aborted (6)
[fv-az1432-100:05460] Signal code:  (-6)
[fv-az1432-100:05460] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f97ece42520]
[fv-az1432-100:05460] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f97ece969fc]
[fv-az1432-100:05460] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f97ece42476]
[fv-az1432-100:05460] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f97ece287f3]
[fv-az1432-100:05460] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f97ed2a2b9e]
[fv-az1432-100:05460] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f97ed2ae20c]
[fv-az1432-100:05460] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f97ed2ae277]
[fv-az1432-100:05460] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f97ed2ae52b]
[fv-az1432-100:05460] [ 8] plumed_master(+0x14274)[0x55f5e1915274]
[fv-az1432-100:05460] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f97ece29d90]
[fv-az1432-100:05460] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f97ece29e40]
[fv-az1432-100:05460] [11] plumed_master(+0x14ed5)[0x55f5e1915ed5]
[fv-az1432-100:05460] *** End of error message ***
</pre>
{% endraw %}
