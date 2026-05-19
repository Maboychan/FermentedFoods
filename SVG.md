
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 300" width="400" height="300">
  <!-- 背景は何も書かなければ透過になります -->
  
  <!-- 傾いた楕円（アンチエイリアスはブラウザやOS側で自動で滑らかに処理されます） -->
  <ellipse cx="200" cy="150" rx="150" ry="75" transform="rotate(-15 200 150)" 
           fill="#ADD8E6" stroke="#0000FF" stroke-width="4" opacity="0.8" />
  
  <!-- ロゴのテキスト -->
  <text x="200" y="160" font-family="sans-serif" font-size="40" font-weight="bold" 
        fill="#0000FF" text-anchor="middle">LOGO</text>
</svg>




<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 400" width="400" height="400">
  
  <!-- 【下絵】手書きの画像を配置（位置やサイズはviewBoxに合わせる） -->
  <!-- opacity="0.4" で薄くして見やすくするのがポイントです -->
  <image href="sketch.jpg" x="0" y="0" width="400" height="400" opacity="0.4" />
  
  <!-- 【清書】下絵を見ながら、ここにSVGの図形を重ねて記述していく -->
  <ellipse cx="200" cy="200" rx="120" ry="60" fill="none" stroke="red" stroke-width="3" />
  
</svg>
![[Pasted image 20260516080716.png]]