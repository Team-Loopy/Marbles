
<h1>GoBlock 5팀 Marbles UI design 변경 </h1>
<hr>


<br>
<br>
<hr>
<h2>🚀[작업환경]</h2>
<img width="1177" alt="작업환경" src="https://user-images.githubusercontent.com/84368302/126476707-8df9c7c4-30d1-4d6f-a2ad-2202e3e5feed.PNG">
<hr>
<br>
<br>
<br>
<br>
<hr>
<h2>🚀[기존 marble UI design의 아쉬움]</h2>
<img width="711" alt="기존마블디자인" src="https://user-images.githubusercontent.com/84368302/126470062-9251dd22-c83b-49e3-b34f-a0110bf7277c.PNG">
<br>
<ul>
  <li>메인화면 최상단에 너무 많은 기능들과 버튼, 글들이 몰려있어 직관적이지 않다.</li>
  <li>한군데 몰려있는 버튼들 때문에 Demo file이 보여주려는 목적이 불분명해 보다.</li>
</ul>

<br>
<br>
<hr>
<h2>🚀[Marbles-Clover Wallet UI]</h2>
<img width="711" alt="메인화면과 타이틀" src="https://user-images.githubusercontent.com/84368302/126471515-8fce71f0-026a-45ee-9ad4-7ecd1110ff19.gif">
<br>
<ul>
  <li>개방감 있는 디자인을 위해 타이틀을 크고 넓게 잡고 눈에 잘보일만한 색상으로 변경 했습니다.</li>
  <li>한군데 몰려있는 버튼을 footer에 내리고 전체적인 UI를 직관적이게 수정 했습니다.</li>
  <li>메인 기능인 자산지갑을 세로로 정렬시키고 프레임을 넓게 잡아 보다 직관적이게 수정 했습니다.</li>
</ul>

<br>
<br>
<hr>
<h2>🚀[What is Clover Wallet]</h2>
<img width="711" alt="로고선정 의미" src="https://user-images.githubusercontent.com/84368302/126471907-daf03d36-fba9-4d9e-a34b-171f27de0170.gif">
<br>

<h3>[Clover wallet 컨셉]</h3>
<p>트럼프 카드에서 Clover는 시민을 뜻합니다.<p>
<p>트럼프 카드게임처럼 오늘날의 블록체인은 오락성과 사행성이 강한 이미지입니다.</p>
<p>Clover wallet은 특정단체나 개인이아닌 참여하는 모든 시민을 위한 분산원장입니다.</p>
<br>

<ul>
  <li>컨셉에 맞게 디자인 적인 측면에서 밝고 화사한 분위기로 구성 했습니다.</li>
  <li>구름으로 이루어진 배경, 알록달록한 자산 등을 동적인 이미지로 구성 했습니다.</li>
  <li>블록체인과 비트코인 이 가지고 있던 부정적이고 도박성이 강한 이미지를 탈피해보고자 바꿨습니다.</li>
</ul>

<br>
<br>
<hr>
<h2>🚀[Marbles 자산 이동]</h2>
<img width="711" alt="로고선정 의미" src="https://user-images.githubusercontent.com/84368302/126476028-b26e0d39-68a7-4ade-b5f9-5daaa1faa050.gif">
<br>
<p>자산으로 표현되는 구슬은 다른 소유주에게 이동이 가능합니다</p>
<ul>
   <li>소유자들에 대한 정보를 담고있는 제이슨파일을 수정하여 저희 팀원들의 이름을 넣어 소유자명을 변경하였습니다.</li>
    <li>자산이동 후 스토리모드 온 설정시 사용자가 지루해 하지않도록 동적인  배경화면 요소를 넣었습니다.</li>
</ul>
    
<br>
<br>
<hr>
<h2>🚀[Marbles 자산 추가]</h2>
<img width="711" alt="로고선정 의미" src="https://user-images.githubusercontent.com/84368302/126477209-784cf374-3b03-4f0a-8e59-a2275b8c3ef8.gif">
<br>
<p>구슬컬러와 사이즈를 선택하여 추가하면 소유자의 지갑에 구슬이 추가됩니다.</p>
<p>기존 구슬 자산의 색상은 너무 단조로워 보였습니다.</p> 
<p> 컨셉에 맞게 다채로워 보이도록 구슬자산들을 그라데이션 색상으로 효과를 주었습니다.</p>
  
   
<br>
<br>
<hr>
<h2>🚀[ CMD에서 조직, 소유자 추가 시연]</h2>
"https://user-images.githubusercontent.com/73014464/126437516-c2e7cf73-9ef0-4d0d-ae3f-85236879e270.mp4"
<br>
<p>1.peer의 보조 명령으로 chaincode명령이 존재하는데 chaincode의 query 명령으로 체인코드에 질의 하고 invoke 명령으로 원장 갱신에 따른 실제 블록체인 트랜잭션을 발생시킴.</p>
<p>2.체인코드를 실행할 때  '채널', '체인코드 이름', '체인코드 API 이름', '체인코드 인수'를 명령으로 지정하는데 여기서는 각각 mychannel, marbles, 'init_owner', 'o123', 'Bob', 'Beedama’ 를 지정해줌.</p>
<p>3.invoke명령 수행 시 -o 옵션을 사용해 오더러를 지정해주고 basic_network 구성에 맞춰 localhost:7050를 지정해줌.</P>
<p>4.수행된 결과를 보면 "Beedama" 사와 자산 소유자 "Bob" 이추가된 것을 확인된걸 볼 수 있음.</p>
<br>
<p>cf.오더러란? 블록체인 네트워크환경에서 트랜잭션 순서제어하는 역할을 수행, 우리 데모에서는 basic_network의 환경을 따르기에 localhost:7050 를 이용했다.</p>




