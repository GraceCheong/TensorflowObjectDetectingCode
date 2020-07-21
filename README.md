# [더하일] Tensorflow 의 Object Detecting 을 사용한 난좌 Defect Detecting SW Demo


1. https://github.com/tensorflow/models 의 공유된 모델 data 사용 

코드를 다운받아 research/object_detecting 폴더만 사용하여도 무방

 $clone https://github.com/tensorflow/models.git



2. obejct.py 의 추가

obejct.py 의 스크립트를 작성하여 추가한다. 
* https://nitr0.tistory.com/266 의 코드를 참고하여야 한다. 


3. object.py 에 tensorflow 문법 변경에 따른 코드 추가 
 
<pre>
<code>
import tensorflow.compat.v1 as tf
tf.disable_v2_behavior()
</pre>
</code>


**  newer version 의 코드와 결합할 때 유의해야하는 사항. 

4. dependency package설치 

 pip3 install numpy tensorflow matplotlib image opencv-python
