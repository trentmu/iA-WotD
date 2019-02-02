<template>
  <div id="app">
    <!-- OuterTable -->
    <table
      align="center"
      cellspacing="0"
      cellpadding="0"
      width="99%"
    >
      <tr>
        <td style="width: 180px; vertical-align: top;  text-align: center;  ">
          <!-- Table(Left) -->
          <table
            align="center"
            cellspacing="0"
            cellpadding="0"
          >
            <tr>
              <td style="vertical-align: top; width: 180px;">
                <img
                  alt="IKFF Africa logo"
                  src="./assets/logo.IKFFafrica.jpg"
                  width="180px"
                >
              </td>
            </tr>
            <tr>
              <td style="
              vertical-align: top; 
              padding: 0px;
              text-align: left; 
              background-color: DimGray; 
              color: white;
              font-size: small;
              ">
                <div style="width: 100%; max-height: 180px; overflow: auto;">
                  <div style="">01. Squats</div>
                  <div style="color: Gold">02. Bridge</div>
                  <div style="font-size: large; background-color: lime; color: blue; font-weight: bolder;">03. Jerks</div>
                  <div style="font-size: medium; background-color: orange;  color: white;">04. Long Cycle</div>
                  <div style="">05. Snatch Left</div>
                  <div style="">06. Snatch Right</div>
                  <div style="">07. OALC Left</div>
                  <div style="">08. OALC Right</div>
                  <div style="">09. Get Up Situp Left</div>
                  <div style="">10. Get Up Situp Right</div>
                  <div style="">11. Double Cleans</div>
                  <div style="">12. Walking Bridge</div>
                  <div style="">13. Tacfit Crab</div>
                </div>
              </td>
            </tr>
          </table>
        </td>
        <td
          width="*"
          style="vertical-align: top; "
        >
          <!-- Table(Right) -->
          <table
            align="center"
            cellspacing="0"
            cellpadding="3"
            width="100%"
          >
            <tr>
              <td style="width: 25%; text-align: left; background-color: blue; color: yellow; font-size: 13px;">Workout Title</td>
              <td style="text-align: left; background-color: blue; color: lime; font-size: 13px; ">Workout Description</td>
            </tr>
          </table>
          <table
            align="center"
            cellspacing="0"
            cellpadding="0"
            width="100%"
          >
            <tr>
              <!-- td: OverallTable: START-->
              <td
                width="65%"
                height="100%"
                style="
                color: red;
                background-color: darkgray; 
                "
              >
                <!-- START: Inner table for OVERALL-->
                <table
                  align="center"
                  cellspacing="0"
                  cellpadding="0"
                  width="100%"
                  height="100%"
                  style="vertical-align: top;"
                >
                  <tr style="vertical-align: top;">
                    <td
                      height="10px"
                      style="
                      text-align: center; 
                      color: red;
                      vertical-align: top;
                      border-style: solid; 
                      border-width: 1px;
                      "
                    >
                      <div style="font-size: 12px">Overall Progress</div>
                    </td>
                  </tr>
                  <tr>
                    <td style="vertical-align: middle; text-align: center;">
                      <span style="color: lightcoral;font-size: 40px;">0: </span>
                      <span style="color: red; font-size: 40px;">13: </span>
                      <span style="color: red; font-size: 40px;">52</span>
                    </td>
                  </tr>
                </table>
                <!-- END: Inner table for OVERALL-->
              </td>
              <!-- td: OverallTable: END-->

              <!-- td: RoundTable: START-->
              <td
                width="*"
                height="100%"
                style="
                color: orange;
                background-color: purple; 
                "
              >
                <!-- START: Inner table for ROUND-->
                <table
                  align="center"
                  cellspacing="0"
                  cellpadding="0"
                  width="100%"
                  height="100%"
                >
                  <tr style="vertical-align: top;">
                    <td
                      height="10px"
                      style="
                      text-align: center; 
                      color: orange;
                      vertical-align: top;
                      border-style: solid; 
                      border-width: 1px;
                      "
                    >
                      <div style="font-size: 12px">Round Progress</div>
                    </td>
                  </tr>
                  <tr>
                    <td style="vertical-align: middle; text-align: center;">
                      <span style="color: orange; font-size: 40px;">08: </span>
                      <span style="color: orange; font-size: 40px;">26</span>
                    </td>
                  </tr>
                </table>
                <!-- END: Inner table for ROUND-->
              </td>
              <!-- td: RoundTable: END -->
            </tr>

            <tr>
              <td
                colspan="1"
                style="
                padding: 1px;
                text-align: center; 
                background-color: lime; 
                color: blue; 
                font-size: 48px;
                border-style: solid;
                border-width: 0px;
                "
              >Jerks</td>
              <td style="
                text-align: left; 
                background-color: lime; 
                color: blue; 
                font-size: 10px;
                border-style: solid;
                border-width: 0px;
                ">next [%Jerk%] in<br>
                <span style="font-size: 32px; color: steelblue;">00.</span>
                <span style="font-size: 36px; color: DodgerBlue;">53</span>
              </td>
            </tr>
            <tr>
              <td
                colspan="2"
                style="
                vertical-align: bottom; 
                text-align: center; 
                background-color: lime; 
                color: blue;
                border-style: solid;
                border-width: 0px;
                "
              >
                <span style="font-size: 80px; color: blue ">01: </span>
                <span style="font-size: 80px; color: blue ">13</span>
              </td>
            </tr>
            <tr>
              <td
                style="width: 100%; height: 16px; text-align: center; background-color: orange; color: white; font-size: x-large"
                colspan="2"
              >Snatch Left</td>
            </tr>
            <tr>
              <td
                style="vertical-align: middle; text-align: center;background-color: black;"
                colspan="2"
              >

                <span style="color: yellow; font-size: 10px;">Skip to the end of this:</span>
              </td>
            </tr>
            <tr>
              <td
                style="vertical-align: middle; text-align: center;background-color: black; "
                colspan="2"
              >
                <button style="color: green; font-size: 12px; padding: 1px">Rep</button>
                <span style="color: white; font-size: 20px;"> | </span>
                <button style="color: orange; font-size: 12px; padding: 1px">Set</button>
                <span style="color: white; font-size: 20px;"> | </span>
                <button style="color: purple; font-size: 12px; padding: 1px">Round</button>
                <span style="color: white; font-size: 20px;"> | </span>
                <button style="color: red; font-size: 12px; padding: 1px">TIME!!</button>
              </td>
            </tr>
          </table>
        </td>
      </tr>
    </table>
  </div>
</template>

<script>
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  text-align: center;
  padding: 0px;
}
</style>