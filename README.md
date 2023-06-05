# roomsandshoots
<div class="grandfather">
  <div class="father">
    <div class="person">
      <div class="children"></div>
      <div class="children"></div>
      <div class="children">
        <div>1</div>
        <div>2</div>
        <div>3</div>
      </div>
    </div>
  </div>
  <div class="uncle">
    <div class="person"></div>
    <div class="person">
      <div class="children"></div>
      <div class="children">
        <div>1</div>
        <div>2</div>
        <div>3</div>
      </div>
      <div class="children"></div>
    </div>
    <div class="person"></div>
  </div>
</div>
.grandfather {
  display: flex;
  justify-content: space-between;
}

.father,
.uncle {
  width: 50%;
  border: 1px solid black;
  padding: 10px;
}

.person {
  border: 1px solid black;
  padding: 10px;
  margin-bottom: 10px;
}

.children {
  border: 1px solid black;
  padding: 10px;
}

.children div {
  font-size: 40px;
}

.uncle {
  text-align: center;
}
