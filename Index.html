<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport"
      content="width=device-width,initial-scale=1,maximum-scale=1">
<title>TradeX — Demo Trading</title>

<style>
*{
  box-sizing:border-box;
  margin:0;
  padding:0;
}

:root{
  --bg:#07101d;
  --panel:#0b1727;
  --panel2:#101f32;
  --border:#1d2d42;
  --text:#fff;
  --muted:#8194ac;
  --green:#20c77a;
  --red:#ef5350;
  --blue:#3b82f6;
  --yellow:#f5b942;
}

body{
  font-family:Arial,Helvetica,sans-serif;
  background:var(--bg);
  color:var(--text);
  min-height:100vh;
}

button,input{
  font:inherit;
}

button{
  cursor:pointer;
}

.demo-banner{
  background:#16283d;
  color:var(--yellow);
  text-align:center;
  padding:7px;
  font-size:11px;
  font-weight:bold;
}

.header{
  height:64px;
  background:var(--panel);
  border-bottom:1px solid var(--border);
  display:flex;
  align-items:center;
  justify-content:space-between;
  padding:0 18px;
}

.logo{
  font-size:25px;
  font-weight:900;
}

.logo span{
  color:var(--green);
}

.header-right{
  display:flex;
  align-items:center;
  gap:10px;
}

.balance-box{
  background:var(--panel2);
  border:1px solid var(--border);
  padding:7px 12px;
  border-radius:7px;
}

.balance-box small{
  display:block;
  color:var(--muted);
  font-size:9px;
}

.balance-box strong{
  color:var(--green);
}

.avatar{
  width:35px;
  height:35px;
  border-radius:50%;
  background:var(--blue);
  display:flex;
  align-items:center;
  justify-content:center;
  font-weight:bold;
}

.app{
  display:flex;
  min-height:calc(100vh - 91px);
}

.sidebar{
  width:210px;
  background:#091522;
  border-right:1px solid var(--border);
  padding:15px 10px;
  flex-shrink:0;
}

.nav{
  width:100%;
  border:0;
  background:transparent;
  color:#8fa1b6;
  padding:12px;
  border-radius:7px;
  text-align:left;
  margin-bottom:4px;
}

.nav:hover,
.nav.active{
  background:#14263b;
  color:#fff;
}

.nav.active{
  border-left:3px solid var(--green);
}

.content{
  flex:1;
  min-width:0;
  padding:18px;
}

.page{
  display:none;
}

.page.active{
  display:block;
}

.page-title{
  font-size:23px;
  margin-bottom:5px;
}

.page-subtitle{
  color:var(--muted);
  font-size:12px;
  margin-bottom:20px;
}

.card{
  background:var(--panel);
  border:1px solid var(--border);
  border-radius:9px;
  padding:16px;
}

.dashboard-grid{
  display:grid;
  grid-template-columns:minmax(0,1fr) 320px;
  gap:15px;
}

.stats{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:10px;
  margin-bottom:15px;
}

.stat{
  background:var(--panel);
  border:1px solid var(--border);
  border-radius:8px;
  padding:14px;
}

.stat small{
  color:var(--muted);
  display:block;
  margin-bottom:7px;
}

.stat strong{
  font-size:18px;
}

.market-bar{
  display:flex;
  justify-content:space-between;
  align-items:center;
  margin-bottom:12px;
}

.market-name{
  font-size:19px;
  font-weight:bold;
}

.market-price{
  color:var(--green);
  margin-top:4px;
}

.timeframes{
  display:flex;
  gap:3px;
}

.timeframes button{
  border:0;
  background:transparent;
  color:var(--muted);
  padding:7px;
}

.timeframes button.active{
  background:#172a40;
  color:#fff;
}

.chart-wrap{
  height:440px;
  position:relative;
}

#chart{
  width:100%;
  height:100%;
}

.chart-info{
  position:absolute;
  top:8px;
  left:8px;
  z-index:2;
  background:rgba(7,16,29,.85);
  padding:7px;
  border-radius:5px;
  color:var(--muted);
  font-size:10px;
}

.chart-info strong{
  color:#fff;
}

.field{
  margin-top:15px;
}

.field label{
  color:var(--muted);
  font-size:11px;
  display:block;
  margin-bottom:6px;
}

.input{
  width:100%;
  background:#07111f;
  color:#fff;
  border:1px solid #293d54;
  border-radius:7px;
  padding:12px;
  outline:none;
}

.quick{
  display:flex;
  gap:5px;
  margin-top:6px;
}

.quick button{
  flex:1;
  border:0;
  background:#16283d;
  color:#a7b6c7;
  padding:7px;
  border-radius:5px;
  font-size:10px;
}

.trade-buttons{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:8px;
  margin-top:15px;
}

.action{
  border:0;
  color:#fff;
  padding:13px;
  border-radius:7px;
  font-weight:bold;
}

.buy{
  background:var(--green);
}

.sell{
  background:var(--red);
}

.deposit{
  background:var(--green);
}

.withdraw{
  background:var(--red);
}

.payout{
  display:flex;
  justify-content:space-between;
  background:#101f32;
  padding:12px;
  border-radius:7px;
  margin-top:15px;
}

.payout span{
  color:var(--muted);
  font-size:11px;
}

.payout strong{
  color:var(--green);
}

.market-list{
  display:grid;
  gap:7px;
}

.market{
  background:#101f32;
  border:1px solid transparent;
  border-radius:7px;
  padding:11px;
  display:flex;
  justify-content:space-between;
  cursor:pointer;
}

.market.active{
  border-color:var(--green);
}

.market small{
  color:var(--muted);
  display:block;
  margin-top:3px;
}

.table-wrap{
  overflow-x:auto;
}

table{
  width:100%;
  border-collapse:collapse;
  min-width:600px;
}

th,
td{
  padding:12px 10px;
  border-bottom:1px solid var(--border);
  text-align:left;
  font-size:12px;
}

th{
  color:var(--muted);
  font-size:10px;
  text-transform:uppercase;
}

.empty{
  text-align:center;
  padding:30px;
  color:var(--muted);
}

.wallet-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:15px;
}

.wallet-balance{
  font-size:30px;
  margin:10px 0;
}

.notice{
  background:#17283d;
  border:1px solid #2b425c;
  color:#a9b8c9;
  padding:12px;
  border-radius:7px;
  font-size:11px;
  line-height:1.5;
  margin-bottom:15px;
}

.form-button{
  width:100%;
  margin-top:12px;
}

.green{
  color:var(--green)!important;
}

.red{
  color:var(--red)!important;
}

.blue{
  color:#60a5fa!important;
}

.yellow{
  color:var(--yellow)!important;
}

.profile{
  max-width:600px;
}

.profile-row{
  display:flex;
  justify-content:space-between;
  padding:14px 0;
  border-bottom:1px solid var(--border);
}

.notification{
  background:#101f32;
  border-left:3px solid var(--green);
  padding:12px;
  margin-bottom:8px;
  border-radius:5px;
}

.notification small{
  display:block;
  color:var(--muted);
  margin-top:5px;
}

/* LOGIN */

.auth{
  min-height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  padding:20px;
}

.auth-box{
  width:100%;
  max-width:420px;
  background:var(--panel);
  border:1px solid var(--border);
  border-radius:14px;
  padding:25px;
}

.auth-box h1{
  text-align:center;
  margin-bottom:5px;
}

.auth-box>.muted{
  text-align:center;
}

.auth-tabs{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:5px;
  margin:20px 0 15px;
}

.auth-tabs button{
  border:0;
  background:#101f32;
  color:var(--muted);
  padding:10px;
  border-radius:6px;
}

.auth-tabs button.active{
  background:#17314a;
  color:#fff;
}

.auth-form{
  display:none;
}

.auth-form.active{
  display:block;
}

.muted{
  color:var(--muted);
  font-size:11px;
}

.demo-note{
  text-align:center;
  color:var(--muted);
  font-size:10px;
  margin-top:15px;
  line-height:1.5;
}

/* MODAL */

.modal{
  position:fixed;
  inset:0;
  background:rgba(0,0,0,.7);
  display:none;
  align-items:center;
  justify-content:center;
  padding:20px;
  z-index:90;
}

.modal-box{
  background:var(--panel);
  border:1px solid var(--border);
  border-radius:10px;
  width:100%;
  max-width:420px;
  padding:20px;
}

.modal-title{
  display:flex;
  justify-content:space-between;
  margin-bottom:15px;
}

.close{
  border:0;
  background:none;
  color:#fff;
  font-size:20px;
}

.toast{
  position:fixed;
  bottom:25px;
  left:50%;
  transform:translateX(-50%);
  background:#182b40;
  border:1px solid #2d455f;
  padding:12px 18px;
  border-radius:8px;
  z-index:100;
  display:none;
  font-size:12px;
}

@media(max-width:1000px){

  .sidebar{
    width:70px;
  }

  .nav span{
    display:none;
  }

  .nav{
    text-align:center;
  }

  .dashboard-grid{
    grid-template-columns:1fr;
  }
}

@media(max-width:700px){

  .header{
    padding:0 10px;
  }

  .logo{
    font-size:21px;
  }

  .sidebar{
    position:fixed;
    bottom:0;
    left:0;
    right:0;
    width:100%;
    height:60px;
    z-index:50;
    display:flex;
    padding:5px;
    border-right:0;
    border-top:1px solid var(--border);
  }

  .nav{
    flex:1;
    margin:0;
    padding:7px 2px;
    font-size:9px;
  }

  .nav span{
    display:block;
    margin-top:3px;
  }

  .content{
    padding:12px;
    padding-bottom:75px;
  }

  .stats{
    grid-template-columns:1fr 1fr;
  }

  .wallet-grid{
    grid-template-columns:1fr;
  }

  .chart-wrap{
    height:360px;
  }

  .market-bar{
    display:block;
  }

  .timeframes{
    margin-top:10px;
  }
}
</style>
</head>

<body>

<!-- LOGIN / SIGN UP -->

<div id="authScreen" class="auth">

<div class="auth-box">

<div class="logo" style="text-align:center">
Trade<span>X</span>
</div>

<h1 id="authTitle">Sign in</h1>

<p class="muted">
Demo trading platform
</p>

<div class="auth-tabs">

<button id="loginTab"
class="active"
onclick="showAuth('login')">
Log in
</button>

<button id="signupTab"
onclick="showAuth('signup')">
Sign up
</button>

</div>

<form id="loginForm"
class="auth-form active"
onsubmit="loginDemo(event)">

<div class="field">

<label>Email</label>

<input
id="loginEmail"
class="input"
type="email"
required
placeholder="you@example.com">

</div>

<div class="field">

<label>Password</label>

<input
class="input"
type="password"
required
placeholder="Password">

</div>

<button
class="action buy form-button"
type="submit">
LOG IN
</button>

</form>

<form id="signupForm"
class="auth-form"
onsubmit="signupDemo(event)">

<div class="field">

<label>Name</label>

<input
id="signupName"
class="input"
required
placeholder="Your name">

</div>

<div class="field">

<label>Email</label>

<input
id="signupEmail"
class="input"
type="email"
required
placeholder="you@example.com">

</div>

<div class="field">

<label>Password</label>

<input
class="input"
type="password"
required
placeholder="Create password">

</div>

<button
class="action buy form-button"
type="submit">
CREATE DEMO ACCOUNT
</button>

</form>

<div class="demo-note">
Demo account only. No real deposits,
withdrawals or real-money payments are enabled.
</div>

</div>
</div>


<!-- APP -->

<div id="appScreen" style="display:none">

<div class="demo-banner">
DEMO MODE • NO REAL MONEY • SIMULATED TRADING
</div>

<header class="header">

<div class="logo">
Trade<span>X</span>
</div>

<div class="header-right">

<div class="balance-box">

<small>
Demo Balance
</small>

<strong id="headerBalance">
$25,430.80
</strong>

</div>

<div
class="avatar"
id="avatar">
T
</div>

</div>

</header>


<div class="app">

<aside class="sidebar">

<button
class="nav active"
onclick="showPage('dashboard',this)">
📊 <span>Dashboard</span>
</button>

<button
class="nav"
onclick="showPage('markets',this)">
💹 <span>Markets</span>
</button>

<button
class="nav"
onclick="showPage('positions',this)">
📈 <span>Positions</span>
</button>

<button
class="nav"
onclick="showPage('wallet',this)">
💰 <span>Wallet</span>
</button>

<button
class="nav"
onclick="showPage('history',this)">
📜 <span>History</span>
</button>

<button
class="nav"
onclick="showPage('notifications',this)">
🔔 <span>Alerts</span>
</button>

<button
class="nav"
onclick="showPage('profile',this)">
👤 <span>Profile</span>
</button>

</aside>


<main class="content">


<!-- DASHBOARD -->

<section
id="dashboard"
class="page active">

<h1 class="page-title">
Trading Dashboard
</h1>

<p class="page-subtitle">
Professional simulated trading environment
</p>


<div class="stats">

<div class="stat">

<small>
Demo Balance
</small>

<strong id="statBalance">
$25,430.80
</strong>

</div>

<div class="stat">

<small>
Open Positions
</small>

<strong id="statPositions">
0
</strong>

</div>

<div class="stat">

<small>
Total Trades
</small>

<strong id="statTrades">
0
</strong>

</div>

<div class="stat">

<small>
Total P/L
</small>

<strong
id="statProfit"
class="green">
$0.00
</strong>

</div>

</div>


<div class="dashboard-grid">


<!-- CHART -->

<div class="card">

<div class="market-bar">

<div>

<div
class="market-name"
id="selectedName">
BTC/USDT
</div>

<div
class="market-price"
id="selectedPrice">
$68,421.30
</div>

</div>

<div class="timeframes">

<button>1m</button>
<button>5m</button>
<button class="active">15m</button>
<button>1H</button>
<button>4H</button>
<button>1D</button>

</div>

</div>


<div class="chart-wrap">

<div class="chart-info">

O:
<strong id="ohlcOpen">0</strong>

&nbsp;

H:
<strong id="ohlcHigh">0</strong>

&nbsp;

L:
<strong id="ohlcLow">0</strong>

&nbsp;

C:
<strong id="ohlcClose">0</strong>

</div>

<canvas id="chart"></canvas>

</div>

</div>


<!-- TRADE PANEL -->

<div class="card">

<h2>
New Trade
</h2>

<p
class="muted"
id="tradeAsset">
BTC/USDT • Demo
</p>


<div class="field">

<label>
Investment Amount
</label>

<input
class="input"
id="investment"
type="number"
min="1"
value="100">


<div class="quick">

<button onclick="setInvestment(10)">
$10
</button>

<button onclick="setInvestment(50)">
$50
</button>

<button onclick="setInvestment(100)">
$100
</button>

<button onclick="setInvestment(500)">
$500
</button>

</div>

</div>


<div class="payout">

<span>
Potential simulated return
</span>

<strong>
+82%
</strong>

</div>


<div class="trade-buttons">

<button
class="action buy"
onclick="openTrade('BUY')">
▲ BUY
</button>

<button
class="action sell"
onclick="openTrade('SELL')">
▼ SELL
</button>

</div>


<div class="notice"
style="margin-top:15px">

This is a simulated trading environment.
No real orders are sent to an exchange.

</div>

</div>

</div>

</section>


<!-- MARKETS -->

<section
id="markets"
class="page">

<h1 class="page-title">
Markets
</h1>

<p class="page-subtitle">
Select a simulated market
</p>

<div class="card">

<div class="market-list">

<div
class="market active"
onclick="selectAsset('BTC/USDT',68421.30,this)">

<div>
<strong>BTC/USDT</strong>
<small>Bitcoin / USDT</small>
</div>

<strong class="green">
$68,421.30
</strong>

</div>


<div
class="market"
onclick="selectAsset('ETH/USDT',3421.76,this)">

<div>
<strong>ETH/USDT</strong>
<small>Ethereum / USDT</small>
</div>

<strong class="green">
$3,421.76
</strong>

</div>


<div
class="market"
onclick="selectAsset('SOL/USDT',178.43,this)">

<div>
<strong>SOL/USDT</strong>
<small>Solana / USDT</small>
</div>

<strong class="green">
$178.43
</strong>

</div>


<div
class="market"
onclick="selectAsset('BNB/USDT',612.28,this)">

<div>
<strong>BNB/USDT</strong>
<small>BNB / USDT</small>
</div>

<strong class="red">
$612.28
</strong>

</div>


<div
class="market"
onclick="selectAsset('XRP/USDT',2.41,this)">

<div>
<strong>XRP/USDT</strong>
<small>XRP / USDT</small>
</div>

<strong class="green">
$2.41
</strong>

</div>


<div
class="market"
onclick="selectAsset('DOGE/USDT',0.21,this)">

<div>
<strong>DOGE/USDT</strong>
<small>Dogecoin / USDT</small>
</div>

<strong class="green">
$0.21
</strong>

</div>

</div>

</div>

</section>


<!-- POSITIONS -->

<section
id="positions"
class="page">

<h1 class="page-title">
Open Positions
</h1>

<p class="page-subtitle">
Monitor your active demo trades
</p>

<div class="card table-wrap">

<table>

<thead>

<tr>

<th>Asset</th>
<th>Direction</th>
<th>Investment</th>
<th>Entry</th>
<th>Current</th>
<th>P/L</th>
<th>Action</th>

</tr>

</thead>

<tbody id="positionsTable">

</tbody>

</table>

</div>

</section>


<!-- WALLET -->

<section
id="wallet"
class="page">

<h1 class="page-title">
Demo Wallet
</h1>

<p class="page-subtitle">
Manage simulated funds
</p>


<div class="notice">

<strong>
DEMO WALLET
</strong>

<br>

Deposits and withdrawals are simulated.
They do not connect to banks, cards,
PayPal or payment processors.

</div>


<div class="wallet-grid">

<div class="card">

<p class="muted">
Available Demo Balance
</p>

<div
class="wallet-balance green"
id="walletBalance">
$25,430.80
</div>

<button
class="action deposit form-button"
onclick="openModal('depositModal')">

+ DEMO DEPOSIT

</button>

</div>


<div class="card">

<p class="muted">
Withdrawable Demo Credits
</p>

<div
class="wallet-balance"
id="withdrawBalance">
$25,430.80
</div>

<button
class="action withdraw form-button"
onclick="openModal('withdrawModal')">

− DEMO WITHDRAWAL

</button>

</div>

</div>


<div
class="card"
style="margin-top:15px">

<h3>
Wallet Activity
</h3>

<div class="table-wrap">

<table>

<thead>

<tr>
<th>Type</th>
<th>Amount</th>
<th>Status</th>
<th>Date</th>
</tr>

</thead>

<tbody id="walletHistory">

</tbody>

</table>

</div>

</div>

</section>


<!-- HISTORY -->

<section
id="history"
class="page">

<h1 class="page-title">
Trade History
</h1>

<p class="page-subtitle">
Completed simulated trades
</p>

<div class="card table-wrap">

<table>

<thead>

<tr>
<th>Asset</th>
<th>Direction</th>
<th>Amount</th>
<th>Entry</th>
<th>Exit</th>
<th>P/L</th>
<th>Time</th>
</tr>

</thead>

<tbody id="historyTable">

</tbody>

</table>

</div>

</section>


<!-- NOTIFICATIONS -->

<section
id="notifications"
class="page">

<h1 class="page-title">
Notifications
</h1>

<p class="page-subtitle">
TradeX activity
</p>

<div id="notificationList">

<div class="notification">

Welcome to TradeX Demo.

<small>
Just now
</small>

</div>

</div>

</section>


<!-- PROFILE -->

<section
id="profile"
class="page">

<h1 class="page-title">
Profile
</h1>

<p class="page-subtitle">
Demo account information
</p>

<div class="card profile">

<div class="profile-row">

<span>
Account
</span>

<strong id="profileName">
TradeX Demo
</strong>

</div>


<div class="profile-row">

<span>
Account Type
</span>

<strong class="yellow">
DEMO
</strong>

</div>


<div class="profile-row">

<span>
Trading Mode
</span>

<strong>
Simulation
</strong>

</div>


<div class="profile-row">

<span>
Real Money
</span>

<strong class="red">
Disabled
</strong>

</div>


<div class="profile-row">

<span>
Payment Processing
</span>

<strong class="red">
Disabled
</strong>

</div>


<button
class="action sell form-button"
onclick="logoutDemo()">

LOG OUT

</button>

</div>

</section>

</main>

</div>

</div>


<!-- DEPOSIT MODAL -->

<div
class="modal"
id="depositModal">

<div class="modal-box">

<div class="modal-title">

<h2>
Demo Deposit
</h2>

<button
class="close"
onclick="closeModal('depositModal')">
×
</button>

</div>

<div class="notice">

This adds simulated credits only.
No real payment is processed.

</div>

<div class="field">

<label>
Amount
</label>

<input
id="depositAmount"
class="input"
type="number"
min="1"
value="100">

</div>

<button
class="action deposit form-button"
onclick="demoDeposit()">

ADD DEMO FUNDS

</button>

</div>

</div>


<!-- WITHDRAW MODAL -->

<div
class="modal"
id="withdrawModal">

<div class="modal-box">

<div class="modal-title">

<h2>
Demo Withdrawal
</h2>

<button
class="close"
onclick="closeModal('withdrawModal')">
×
</button>

</div>

<div class="notice">

Real-money and PayPal withdrawals are disabled.
This only removes demo credits.

</div>

<div class="field">

<label>
Amount
</label>

<input
id="withdrawAmount"
class="input"
type="number"
min="1"
value="100">

</div>

<div class="field">

<label>
Demo destination
</label>

<input
id="withdrawEmail"
class="input"
type="email"
placeholder="demo@example.com">

</div>

<button
class="action withdraw form-button"
onclick="demoWithdraw()">

SIMULATE WITHDRAWAL

</button>

</div>

</div>


<div
id="toast"
class="toast">
</div>


<script>

/* =========================
   ACCOUNT
========================= */

let account=null;

let balance=25430.80;

let selectedAsset="BTC/USDT";

let selectedBasePrice=68421.30;

let chartPrice=68421.30;

let chartHistory=[];

let positions=[];

let tradeHistory=[];

let walletHistory=[];


function money(n){

return "$"+
Number(n||0).toLocaleString(
undefined,
{
minimumFractionDigits:2,
maximumFractionDigits:2
}
);

}


/* =========================
   AUTH
========================= */

function showAuth(type){

document
.getElementById("loginForm")
.classList
.toggle("active",type==="login");

document
.getElementById("signupForm")
.classList
.toggle("active",type==="signup");

document
.getElementById("loginTab")
.classList
.toggle("active",type==="login");

document
.getElementById("signupTab")
.classList
.toggle("active",type==="signup");

document
.getElementById("authTitle")
.textContent=
type==="login"
?"Sign in"
:"Create account";

}


function loginDemo(e){

e.preventDefault();

const email=
document
.getElementById("loginEmail")
.value;

account={
name:email.split("@")[0]||"Trader",
email:email
};

enterApp();

}


function signupDemo(e){

e.preventDefault();

account={
name:
document
.getElementById("signupName")
.value,

email:
document
.getElementById("signupEmail")
.value
};

enterApp();

}


function enterApp(){

document
.getElementById("authScreen")
.style.display="none";

document
.getElementById("appScreen")
.style.display="block";

document
.getElementById("profileName")
.textContent=account.name;

document
.getElementById("avatar")
.textContent=
account.name
.charAt(0)
.toUpperCase();

updateUI();

}


function logoutDemo(){

account=null;

document
.getElementById("appScreen")
.style.display="none";

document
.getElementById("authScreen")
.style.display="flex";

showAuth("login");

}


/* =========================
   NAVIGATION
========================= */

function showPage(id,btn){

document
.querySelectorAll(".page")
.forEach(
p=>p.classList.remove("active")
);

document
.getElementById(id)
.classList.add("active");

document
.querySelectorAll(".nav")
.forEach(
n=>n.classList.remove("active")
);

btn.classList.add("active");

}


/* =========================
   TRADING
========================= */

function setInvestment(n){

document
.getElementById("investment")
.value=n;

}


function selectAsset(name,price,el){

selectedAsset=name;

selectedBasePrice=price;

chartPrice=price;

document
.getElementById("selectedName")
.textContent=name;

document
.getElementById("selectedPrice")
.textContent=money(price);

document
.getElementById("tradeAsset")
.textContent=
name+" • Demo";

document
.querySelectorAll(".market")
.forEach(
m=>m.classList.remove("active")
);

if(el){
el.classList.add("active");
}

createInitialData();

drawChart();

}


function openTrade(direction){

const amount=
Number(
document
.getElementById("investment")
.value
);

if(!amount||amount<=0){

toast("Enter a valid amount");

return;

}

if(amount>balance){

toast("Insufficient demo balance");

return;

}

const entry=chartPrice;

balance-=amount;

positions.push({

id:Date.now(),

asset:selectedAsset,

direction:direction,

amount:amount,

entry:entry,

current:entry

});

addNotification(
direction+
" demo trade opened on "+
selectedAsset
);

updateUI();

toast(
direction+
" demo trade opened"
);

}


function closePosition(id){

const index=
positions.findIndex(
p=>p.id===id
);

if(index<0)return;

const p=positions[index];

const exit=chartPrice;

const move=
p.direction==="BUY"
?exit-p.entry
:p.entry-exit;

const pnl=
p.amount*
(move/p.entry)*
0.82;

balance+=
p.amount+
Math.max(0,pnl);

tradeHistory.unshift({

asset:p.asset,

direction:p.direction,

amount:p.amount,

entry:p.entry,

exit:exit,

pnl:pnl,

time:new Date()
.toLocaleString()

});

positions.splice(index,1);

addNotification(
"Demo position closed: "+
p.asset
);

updateUI();

toast("Demo position closed");

}


/* =========================
   UI
========================= */

function updateUI(){

document
.getElementById("headerBalance")
.textContent=money(balance);

document
.getElementById("statBalance")
.textContent=money(balance);

document
.getElementById("walletBalance")
.textContent=money(balance);

document
.getElementById("withdrawBalance")
.textContent=money(balance);

document
.getElementById("statPositions")
.textContent=
positions.length;

document
.getElementById("statTrades")
.textContent=
tradeHistory.length+
positions.length;

updatePositions();

renderWalletHistory();

renderHistory();

}


function updatePositions(){

let total=0;

positions.forEach(p=>{

if(p.asset===selectedAsset){

p.current=chartPrice;

}

const move=
p.direction==="BUY"
?p.current-p.entry
:p.entry-p.current;

total+=
p.amount*
(move/p.entry)*
0.82;

});

const profit=
document
.getElementById("statProfit");

profit.textContent=money(total);

profit.className=
total>=0
?"green"
:"red";


const table=
document
.getElementById("positionsTable");


if(!positions.length){

table.innerHTML=
`<tr>
<td colspan="7" class="empty">
No open positions.
</td>
</tr>`;

return;

}


table.innerHTML=
positions.map(p=>{

const move=
p.direction==="BUY"
?p.current-p.entry
:p.entry-p.current;

const pnl=
p.amount*
(move/p.entry)*
0.82;

return `
<tr>

<td>${p.asset}</td>

<td class="${
p.direction==="BUY"
?"green"
:"red"
}">
${p.direction}
</td>

<td>${money(p.amount)}</td>

<td>${p.entry.toFixed(2)}</td>

<td>${p.current.toFixed(2)}</td>

<td class="${
pnl>=0
?"green"
:"red"
}">
${money(pnl)}
</td>

<td>

<button
class="action sell"
style="padding:7px"
onclick="closePosition(${p.id})">

CLOSE

</button>

</td>

</tr>
`;

}).join("");

}


/* =========================
   DEMO WALLET
========================= */

function demoDeposit(){

const amount=
Number(
document
.getElementById("depositAmount")
.value
);

if(!amount||amount<=0){

toast("Enter a valid amount");

return;

}

balance+=amount;

walletHistory.unshift({

type:"Demo deposit",

amount:amount,

status:"SIMULATED",

date:new Date()
.toLocaleString()

});

closeModal("depositModal");

updateUI();

addNotification(
"Demo deposit added: "+
money(amount)
);

toast("Demo funds added");

}


function demoWithdraw(){

const amount=
Number(
document
.getElementById("withdrawAmount")
.value
);

const email=
document
.getElementById("withdrawEmail")
.value;

if(!amount||amount<=0){

toast("Enter a valid amount");

return;

}

if(amount>balance){

toast("Insufficient demo balance");

return;

}

if(!email){

toast("Enter a demo email");

return;

}

balance-=amount;

walletHistory.unshift({

type:"Demo withdrawal",

amount:-amount,

status:"SIMULATED",

date:new Date()
.toLocaleString()

});

closeModal("withdrawModal");

updateUI();

addNotification(
"Demo withdrawal simulated"
);

toast(
"Demo withdrawal simulated"
);

}


function renderWalletHistory(){

const table=
document
.getElementById("walletHistory");

if(!walletHistory.length){

table.innerHTML=
`<tr>
<td colspan="4" class="empty">
No wallet activity yet.
</td>
</tr>`;

return;

}

table.innerHTML=
walletHistory.map(x=>`

<tr>

<td>${x.type}</td>

<td>
${money(Math.abs(x.amount))}
</td>

<td>${x.status}</td>

<td>${x.date}</td>

</tr>

`).join("");

}


function renderHistory(){

const table=
document
.getElementById("historyTable");

if(!tradeHistory.length){

table.innerHTML=
`<tr>
<td colspan="7" class="empty">
No completed trades yet.
</td>
</tr>`;

return;

}

table.innerHTML=
tradeHistory.map(x=>`

<tr>

<td>${x.asset}</td>

<td class="${
x.direction==="BUY"
?"green"
:"red"
}">
${x.direction}
</td>

<td>${money(x.amount)}</td>

<td>${x.entry.toFixed(2)}</td>

<td>${x.exit.toFixed(2)}</td>

<td class="${
x.pnl>=0
?"green"
:"red"
}">
${money(x.pnl)}
</td>

<td>${x.time}</td>

</tr>

`).join("");

}


/* =========================
   NOTIFICATIONS
========================= */

function addNotification(text){

document
.getElementById("notificationList")
.insertAdjacentHTML(
"afterbegin",

`
<div class="notification">

${text}

<small>
Just now
</small>

</div>
`
);

}


/* =========================
   MODALS
========================= */

function openModal(id){

document
.getElementById(id)
.style.display="flex";

}


function closeModal(id){

document
.getElementById(id)
.style.display="none";

}


/* =========================
   TOAST
========================= */

function toast(message){

const t=
document
.getElementById("toast");

t.textContent=message;

t.style.display="block";

clearTimeout(window.toastTimer);

window.toastTimer=
setTimeout(
()=>t.style.display="none",
2500
);

}


/* =========================
   MOVING CHART
========================= */

const canvas=
document.getElementById("chart");

const ctx=
canvas.getContext("2d");


function resizeChart(){

const rect=
canvas.getBoundingClientRect();

const ratio=
window.devicePixelRatio||1;

canvas.width=
rect.width*ratio;

canvas.height=
rect.height*ratio;

ctx.setTransform(
ratio,
0,
0,
ratio,
0,
0
);

}


function createInitialData(){

chartHistory=[];

let price=
selectedBasePrice;

for(let i=0;i<70;i++){

const open=price;

const change=
(Math.random()-.48)*
price*
.003;

const close=
open+change;

const high=
Math.max(open,close)+
Math.random()*
price*
.0015;

const low=
Math.min(open,close)-
Math.random()*
price*
.0015;

chartHistory.push({

open,
high,
low,
close

});

price=close;

}

chartPrice=price;

}


function updateChart(){

const last=
chartHistory[
chartHistory.length-1
];

const open=
last.close;

const change=
(Math.random()-.48)*
chartPrice*
.0015;

const close=
open+change;

const high=
Math.max(open,close)+
Math.random()*
chartPrice*
.0008;

const low=
Math.min(open,close)-
Math.random()*
chartPrice*
.0008;

chartHistory.push({

open,
high,
low,
close

});

if(chartHistory.length>80){

chartHistory.shift();

}

chartPrice=close;

document
.getElementById("selectedPrice")
.textContent=money(chartPrice);

document
.getElementById("ohlcOpen")
.textContent=open.toFixed(2);

document
.getElementById("ohlcHigh")
.textContent=high.toFixed(2);

document
.getElementById("ohlcLow")
.textContent=low.toFixed(2);

document
.getElementById("ohlcClose")
.textContent=close.toFixed(2);

updatePositions();

drawChart();

}


function drawChart(){

const width=
canvas.clientWidth;

const height=
canvas.clientHeight;

if(!chartHistory.length)return;

const highest=
Math.max(
...chartHistory.map(x=>x.high)
);

const lowest=
Math.min(
...chartHistory.map(x=>x.low)
);

const padding=35;

const range=
highest-lowest||1;


function y(price){

return padding+
(highest-price)/
range*
(height-padding*2);

}


ctx.clearRect(
0,
0,
width,
height
);


/* GRID */

ctx.strokeStyle=
"rgba(120,150,180,.12)";

ctx.lineWidth=1;

for(let i=0;i<6;i++){

const gy=
padding+
i*
(height-padding*2)/5;

ctx.beginPath();

ctx.moveTo(0,gy);

ctx.lineTo(width,gy);

ctx.stroke();

}


/* CANDLES */

const candleWidth=
Math.max(
3,
(width-20)/
chartHistory.length*
.65
);

const spacing=
(width-20)/
chartHistory.length;


chartHistory.forEach(
(c,index)=>{

const x=
10+
index*
spacing+
spacing/2;

const openY=y(c.open);

const closeY=y(c.close);

const highY=y(c.high);

const lowY=y(c.low);

const rising=
c.close>=c.open;

ctx.strokeStyle=
rising
?"#20c77a"
:"#ef5350";

ctx.fillStyle=
ctx.strokeStyle;


/* WICK */

ctx.beginPath();

ctx.moveTo(x,highY);

ctx.lineTo(x,lowY);

ctx.stroke();


/* BODY */

ctx.fillRect(

x-candleWidth/2,

Math.min(
openY,
closeY
),

candleWidth,

Math.max(
2,
Math.abs(
closeY-openY
)
)

);

});


/* CURRENT PRICE */

const currentY=
y(chartPrice);

ctx.strokeStyle=
"#f5b942";

ctx.setLineDash(
[5,5]
);

ctx.beginPath();

ctx.moveTo(
0,
currentY
);

ctx.lineTo(
width,
currentY
);

ctx.stroke();

ctx.setLineDash([]);

ctx.fillStyle=
"#f5b942";

ctx.font=
"11px Arial";

ctx.fillText(
money(chartPrice),
width-90,
currentY-5
);

}


/* START */

resizeChart();

createInitialData();

drawChart();


/* MOVE EVERY SECOND */

setInterval(
updateChart,
1000
);


window.addEventListener(
"resize",
()=>{
resizeChart();
drawChart();
}
);

</script>

</body>
</html>
