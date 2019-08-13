<template>
  <div id="app">
    <b-container fluid class='blue' >
      <b-row>
        <b-col class="blue" xs='12'>
          <img src="./assets/heidelberg_catechism.svg"  width='1200' style="padding-top: 100px;position: relative;">
        </b-col>
      </b-row>
      <b-row id='title1'>
        <b-col md='8' offset-md='2' style='padding-top:75px'>
        
        <h4><i>Christian Instruction, according to the Usages of the Churches and Schools of the Electoral Palatinate</i></h4>
        </b-col>
      </b-row>
      
      <b-row >
        <b-col cols="12"  >
          <div tabs justified  v-b-scrollspy:nav-scroller >
          <b-nav-item href="#1">Day 01</b-nav-item>
          <b-nav-item href="#3">Day 02</b-nav-item>
          <b-nav-item href="#6">Day 03</b-nav-item>
          <b-nav-item href="#9">Day 04</b-nav-item>
          <b-nav-item href="#12">Day 05</b-nav-item>
          <b-nav-item href="#16">Day 06</b-nav-item>
          <b-nav-item href="#20">Day 07</b-nav-item>
          <b-nav-item href="#24">Day 08</b-nav-item>
          <b-nav-item href="#26">Day 09</b-nav-item>
          <b-nav-item href="#27">Day 10</b-nav-item>
          <b-nav-item href="#29">Day 11</b-nav-item>
          <b-nav-item href="#31">Day 12</b-nav-item>
          <b-nav-item href="#33">Day 13</b-nav-item>
          <b-nav-item href="#35">Day 14</b-nav-item>
          <b-nav-item href="#37">Day 15</b-nav-item>
          <b-nav-item href="#40">Day 16</b-nav-item>
          <b-nav-item href="#45">Day 17</b-nav-item>
          <b-nav-item href="#46">Day 18</b-nav-item>
          <b-nav-item href="#50">Day 19</b-nav-item>
          <b-nav-item href="#53">Day 20</b-nav-item>
          <b-nav-item href="#54">Day 21</b-nav-item>
          <b-nav-item href="#57">Day 22</b-nav-item>
          <b-nav-item href="#59">Day 23</b-nav-item>
          <b-nav-item href="#62">Day 24</b-nav-item>
          <b-nav-item href="#65">Day 25</b-nav-item>
          <b-nav-item href="#69">Day 26</b-nav-item>
          <b-nav-item href="#72">Day 27</b-nav-item>
          <b-nav-item href="#75">Day 28</b-nav-item>
          <b-nav-item href="#78">Day 29</b-nav-item>
          <b-nav-item href="#80">Day 30</b-nav-item>
          <b-nav-item href="#83">Day 31</b-nav-item>
          <b-nav-item href="#86">Day 32</b-nav-item>
          <b-nav-item href="#88">Day 33</b-nav-item>
          <b-nav-item href="#92">Day 34</b-nav-item>
          <b-nav-item href="#96">Day 35</b-nav-item>
          <b-nav-item href="#99">Day 36</b-nav-item>
          <b-nav-item href="#101">Day 37</b-nav-item>
          <b-nav-item href="#103">Day 38</b-nav-item>
          <b-nav-item href="#104">Day 39</b-nav-item>
          <b-nav-item href="#105">Day 40</b-nav-item>
          <b-nav-item href="#108">Day 41</b-nav-item>
          <b-nav-item href="#110">Day 42</b-nav-item>
          <b-nav-item href="#112">Day 43</b-nav-item>
          <b-nav-item href="#113">Day 44</b-nav-item>
          <b-nav-item href="#116">Day 45</b-nav-item>
          <b-nav-item href="#120">Day 46</b-nav-item>
          <b-nav-item href="#122">Day 47</b-nav-item>
          <b-nav-item href="#123">Day 48</b-nav-item>
          <b-nav-item href="#124">Day 49</b-nav-item>
          <b-nav-item href="#125">Day 50</b-nav-item>
          <b-nav-item href="#126">Day 51</b-nav-item>
          <b-nav-item href="#127">Day 52</b-nav-item>
        </div>
        </b-col>
      </b-row>
      <b-row>
        <b-col xs='4' offset-xs='4'>
          <a href='#1'><unicon name="angle-down" fill='#858170' height="50" width="50" /></a>
        </b-col>
      </b-row>
    </b-container >
    <b-container fluid>
      <b-row>
      <b-col cols="2" class="d-none d-lg-block">
        <b-list-group v-b-scrollspy:listgroup-ex style='text-align:left !important; padding-top: 15px; padding-bottom:15px'>
          <b-list-group-item href="#1">Day 1</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#1">Q01</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#2">Q02</b-list-group-item>
          <b-list-group-item href="#3">Day 2</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#3">Q03</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#4">Q04</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#5">Q05</b-list-group-item>
          <b-list-group-item href="#6">Day 3</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#6">Q06</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#7">Q07</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#8">Q08</b-list-group-item>
          <b-list-group-item href="#9">Day 4</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#9">Q09</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#10">Q10</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#11">Q11</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#12">Day 5</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#12">Q12</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#13">Q13</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#14">Q14</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#15">Q15</b-list-group-item>
          <b-list-group-item href="#16">Day 6</b-list-group-item>
          <b-list-group-item style='padding-left:45px' ref="#16">Q16</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#17">Q17</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#18">Q18</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#19">Q19</b-list-group-item>
          <b-list-group-item href="#20">Day 7</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#20">Q20</b-list-group-item>
          <b-list-group-item style='padding-left:45px' href="#21">Q21</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#22">Q22</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#23">Q23</b-list-group-item>
          <b-list-group-item href="#24">Day 8</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#24">Q24</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#25">Q25</b-list-group-item>
          <b-list-group-item  href="#26">Day 9</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#26">Q26</b-list-group-item>
          <b-list-group-item  href="#27">Day 10</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#27">Q27</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#28">Q28</b-list-group-item>
          <b-list-group-item  href="#29">Day 11</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#29">Q29</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#30">Q30</b-list-group-item>
          <b-list-group-item  href="#31">Day 12</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#31">Q31</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#32">Q32</b-list-group-item>
          <b-list-group-item  href="#33">Day 13</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#33">Q33</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#34">Q34</b-list-group-item>
          <b-list-group-item  href="#35">Day 14</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#35">Q35</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#36">Q36</b-list-group-item>
          <b-list-group-item  href="#37">Day 15</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#37">Q37</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#38">Q38</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#39">Q39</b-list-group-item>
          <b-list-group-item  href="#40">Day 16</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#40">Q40</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#41">Q41</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#42">Q42</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#43">Q43</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#44">Q44</b-list-group-item>
          <b-list-group-item  href="#45">Day 17</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#45">Q45</b-list-group-item>
          <b-list-group-item  href="#46">Day 18</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#46">Q46</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#47">Q47</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#48">Q48</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#49">Q49</b-list-group-item>
          <b-list-group-item  href="#50">Day 19</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#50">Q50</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#51">Q51</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#52">Q52</b-list-group-item>
          <b-list-group-item  href="#53">Day 20</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#53">Q53</b-list-group-item>
          <b-list-group-item  href="#54">Day 21</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#54">Q54</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#55">Q55</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#56">Q56</b-list-group-item>
          <b-list-group-item  href="#57">Day 22</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#57">Q57</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#58">Q58</b-list-group-item>
          <b-list-group-item  href="#59">Day 23</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#59">Q59</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#60">Q60</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#61">Q61</b-list-group-item>
          <b-list-group-item  href="#62">Day 24</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#62">Q62</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#63">Q63</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#64">Q64</b-list-group-item>
          <b-list-group-item  href="#65">Day 25</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#65">Q65</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#66">Q66</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#67">Q67</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#68">Q68</b-list-group-item>
          <b-list-group-item  href="#69">Day 26</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#69">Q69</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#70">Q70</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#71">Q71</b-list-group-item>
          <b-list-group-item  href="#72">Day 27</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#72">Q72</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#73">Q73</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#74">Q74</b-list-group-item>
          <b-list-group-item  href="#75">Day 28</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#75">Q75</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#76">Q76</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#77">Q77</b-list-group-item>
          <b-list-group-item  href="#78">Day 29</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#78">Q78</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#79">Q79</b-list-group-item>
          <b-list-group-item  href="#80">Day 30</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#80">Q80</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#81">Q81</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#82">Q82</b-list-group-item>
          <b-list-group-item  href="#83">Day 31</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#83">Q83</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#84">Q84</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#85">Q85</b-list-group-item>
          <b-list-group-item  href="#86">Day 32</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#86">Q86</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#87">Q87</b-list-group-item>
          <b-list-group-item  href="#88">Day 33</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#88">Q88</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#89">Q89</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#90">Q90</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#91">Q91</b-list-group-item>
          <b-list-group-item  href="#92">Day 34</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#92">Q92</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#93">Q93</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#94">Q94</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#95">Q95</b-list-group-item>
          <b-list-group-item  href="#96">Day 35</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#96">Q96</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#97">Q97</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#98">Q98</b-list-group-item>
          <b-list-group-item   href="#99">Day 36</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#99">Q99</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#100">Q100</b-list-group-item>
          <b-list-group-item  href="#101">Day 37</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#101">Q101</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#102">Q102</b-list-group-item>
          <b-list-group-item  href="#103">Days 38 & 39</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#103">Q103</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#104">Q104</b-list-group-item>
          <b-list-group-item  href="#105">Day 40</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#105">Q105</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#106">Q106</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#107">Q107</b-list-group-item>
          <b-list-group-item  href="#108">Day 41</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#108">Q108</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#109">Q109</b-list-group-item>
          <b-list-group-item  href="#110">Day 42</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#110">Q110</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#111">Q111</b-list-group-item>
          <b-list-group-item href="#112">Day 43</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#112">Q112</b-list-group-item>
          <b-list-group-item  href="#113">Day 44</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#113">Q113</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#114">Q114</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#115">Q115</b-list-group-item>
          <b-list-group-item  href="#116">Day 45</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#116">Q116</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#117">Q117</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#118">Q118</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#119">Q119</b-list-group-item>
          <b-list-group-item  href="#120">Day 46</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#120">Q120</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#121">Q121</b-list-group-item>
          <b-list-group-item  href="#122">Days 47 - 51</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#122">Q122</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#123">Q123</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#124">Q124</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#125">Q125</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#126">Q126</b-list-group-item>
          <b-list-group-item  href="#127">Day 52</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#127">Q127</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#128">Q128</b-list-group-item>
          <b-list-group-item style='padding-left:45px'  href="#129">Q129</b-list-group-item>
        </b-list-group>
      </b-col>
    <b-col lg="10" md='12' style='padding-top: 20px'>
    <div id="listgroup-ex" style="position:relative; overflow-y:auto; height:8630px;">
    <b-container id='1' fluid style="padding-top:200px; padding-bottom:200px;">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>1. What is thy only comfort in life and in death? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That I, with body and soul, both in life and in death, am not my own, but belong to my faithful Savior Jesus Christ, who with His precious blood has fully satisfied for all my sins, and redeemed me from all the power of the devil; and so preserves me, that without the will of my Father in heaven not a hair can fall from my head; yea, that all things must work together for my salvation. Wherefore, by His Holy Spirit, He also assures me of eternal life, and makes me heartily willing and ready henceforth to live unto Him.
          </h4>
        </b-col>
      </b-row>
      
    </b-container>
    
    <b-container id='2' fluid class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4 ><b>2. How many things are necessary for thee to know, that thou in this comfort mayest live and die happily? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Three things: first, the greatness of my sin and misery. Second, how I am redeemed from all my sins and misery. Third, how I am to be thankful to God for such redemption.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container id='3' fluid style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>3. Whence knowest thou thy misery? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Out of the Law of God.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='4' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>4. What does the Law of God require of us? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Christ teaches us in sum, Matthew 22:37–40, “Thou shalt love the Lord, thy God with all thy heart, and with all thy soul, and with all thy mind, and with all thy strength. This is the first and great commandment; and the second is like unto it: Thou shalt love thy neighbor as thyself. On these two commandments hang all the law and the prophets.”
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='5' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>5. Canst thou keep all this perfectly? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No: for I am by nature prone to hate God and my neighbor.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid id='6' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>6. Did God create man thus wicked and perverse? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No, but God created man good, and after His own image, that is, in righteousness and true holiness; that he might rightly know God his Creator, heartily love Him, and live with Him in eternal blessedness, to praise and glorify Him.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='7' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>7. Whence then comes this depraved nature of man? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          From the fall and disobedience of our first parents, Adam and Eve, in Paradise, whereby our nature became so corrupt, that we are all conceived and born in sin.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='8' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>8. But are we so depraved, that we are wholly unapt to any good and prone to all evil?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Yes; unless we are born again by the Spirit of God.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='9' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>9. Does not God then wrong man, by requiring of him in His law that which he cannot perform? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No: for God so made man, that he could perform it; but man, through the instigation of the devil, by wilful disobedience deprived himself and all his posterity of this power.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='10' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>10. Will God suffer such disobedience and apostasy to go unpunished? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          By no means; but He is terribly displeased with our inborn as well as our actual sins, and will punish them in just judgment in time and eternity, as he has declared: Cursed is everyone that continueth not in all things which are written in the book of the law, to do them (Deut. 27:26). 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='11' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>11. Is then God not merciful? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          God is indeed merciful, but He is likewise just; wherefore His justice requires that sin, which is committed against the most high majesty of God, be also punished with extreme, that is, with everlasting punishment both of body and soul. 
          </h4>
        </b-col>
      </b-row>
      
    </b-container>
    
    <b-container fluid  id='12' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>12. Since then, by the righteous judgment of God, we deserve temporal and eternal punishment, what is required that we may escape this punishment and be again received into favor? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          God wills that His justice be satisfied, therefore we must make full satisfaction to the same, either by ourselves or by another
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid   id='13' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>13. Can we ourselves make this satisfaction? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          By no means: on the contrary, we daily increase our guilt.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='14' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>14. Can any mere creature make satisfaction for us? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          None: for first, God will not punish, in any other creature, that of which man has made himself guilty; and further, no mere creature can sustain the burden of God’s eternal wrath against sin, and redeem others therefrom.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='15'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>15. What manner of mediator and redeemer then must we seek?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          One who is a true and sinless man, and yet more powerful than all creatures, that is, one who is at the same time true God. 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='16' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>16. Why must He be a true and sinless man? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Because the justice of God requires, that the same human nature which has sinned should make satisfaction for sin; but no man, being himself a sinner, could satisfy for others.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='17'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>17. Why must He be at the same time true God?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That by the power of His Godhead He might bear in His manhood the burden of God’s wrath and so obtain for and restore to us righteousness and life.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='18' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>18. But who now is that Mediator, who is at the same time true God and a true, sinless man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Our Lord Jesus Christ, who is freely given unto us for complete redemption and righteousness.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='19'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>19. Whence knowest thou this?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          From the Holy Gospel: which God Himself first revealed in Paradise; afterwards proclaimed by the holy Patriarchs and Prophets, and foreshadowed by the sacrifices and other ceremonies of the law; and finally fulfilled by His well-beloved Son. 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='20' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>20. Are all men then saved by Christ, as they have perished in Adam?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No; only such as by true faith are ingrafted into Him, and receive all His benefits.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='21'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>21. What is true faith?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          It is not only a certain knowledge, whereby I hold for truth all that God has revealed to us in His Word; but also a hearty trust, which the Holy Ghost works in me by the Gospel, that not only to others, but to me also, forgiveness of sins, everlasting righteousness and salvation, are freely given by God, merely of grace, for the sake of Christ’s merits.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='22' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>22. What is then necessary for a Christian to believe? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          All that is promised us in the Gospel, which the articles of our catholic, undoubted Christian faith teach us in sum.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='23'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>23. What are these Articles? ?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          I believe in God the Father Almighty, Maker of heaven and earth.<p />
          And in Jesus Christ, His only begotten Son, our Lord: who was conceived by the Holy Ghost, born of the virgin Mary; suffered under Pontius Pilate, was crucified, dead and buried; He descended into hell; the third day He rose from the dead; He ascended into heaven, and sitteth at the right hand of God the Father Almighty; from thence He shall come to judge the quick and the dead.<p />
          I believe in the Holy Ghost; the holy catholic Church; the communion of saints; the forgiveness of sins; the resurrection of the body, and the life everlasting.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='24' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>24. How are these articles divided? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Into three parts: the first is of God the Father, and our creation; the second, of God the Son, and our redemption; the third, of God the Holy Ghost, and our sanctification.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='25'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>25. Since there is but one Divine Being, why speakest thou of three, Father, Son and Holy Ghost? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Because God has so revealed Himself in His Word, that these three distinct Persons are the one, true, eternal God.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='26' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>26. What dost thou believe when thou sayest: I believe in God the Father Almighty, Maker of heaven and earth?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That the eternal Father of our Lord Jesus Christ, who of nothing made heaven and earth, with all that in them is, who likewise upholds and governs the same by His eternal counsel and providence, is for the sake of Christ His Son my God and my Father; in whom I so trust, as to have no doubt that He will provide me with all things necessary for body and soul; and further, that whatever evil He sends upon me in this vale of tears He will turn to my good; for He is able to do it, being Almighty God, and willing also, being a faithful Father.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='27'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>27. What dost thou understand by the Providence of God?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          The almighty everywhere present power of God, whereby, as it were by His hand, He still upholds heaven and earth, with all creatures; and so governs them, that herbs and grass, rain and drought, fruitful and barren years, meat and drink, health and sickness, riches and poverty, yea, all things, come not by chance, but by His fatherly hand.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='28' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>28. What does it profit us to know that God has created, and by His providence still upholds all things? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That we may be patient in adversity; thankful in prosperity; and for what is future, have good confidence in our faithful God and Father, that no creature shall separate us from His love; since all creatures are so in His hand, that without His will they cannot so much as move.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='29'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>29. Why is the Son of God called Jesus, that is, Savior? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Because He saves us from our sins; and no salvation is to be either sought or found in any other.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='30' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>30. Do such then believe in the only Savior Jesus, who seek their salvation and welfare of saints, of themselves, or anywhere else?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No; although they may make their boast of Him, yet in act they deny the only Savior Jesus. For either Jesus is not a complete Savior, or they who by true faith receive this Savior, must have in Him all that is necessary to their salvation. 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='31'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>31. Why is He called Christ, that is, Anointed?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Because He is ordained of God the Father, and anointed with the Holy Ghost, to be our chief Prophet and Teacher, who fully reveals to us the secret counsel and will of God concerning our redemption; and our only High Priest, who by the one sacrifice of His body has redeemed us, and ever liveth to make intercession for us with the Father; and our eternal King, who governs us by His Word and Spirit, and defends and preserves us in the redemption obtained for us.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='32' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>32. But why art thou called a Christian?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Because by faith I am a member of Christ, and thus a partaker of His anointing; in order that I also may confess His name; may present myself a living sacrifice of thankfulness to Him; and may with free conscience fight against sin and the devil in this life, and hereafter, in eternity, reign with Him over all creatures. 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='33'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>33. Why is He called God’s only begotten Son, since we also are the children of God?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Because Christ alone is the eternal, natural Son of God; but we are the children of God by adoption through grace for His sake.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='34' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>34. Why callest thou Him our Lord?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
           Because, not with silver and gold, but with His precious blood, He has redeemed and purchased us, body and soul, from sin and from all the power of the devil, to be His own.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='35'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>35. What is the meaning of: Conceived by the Holy Ghost, born of the virgin Mary? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That the eternal Son of God, who is and continues true and eternal God, took upon Him the very nature of man, of the flesh and blood of the virgin Mary, by the operation of the Holy Ghost; so that He also might be the true seed of David, like unto His brethren in all things, sin excepted. 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='36' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>36. What benefit dost thou receive from the holy conception and birth of Christ?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That He is our Mediator, and with His innocence and perfect holiness covers, in the sight of God, my sin, wherein I was conceived.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='37'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>37. What dost thou understand by the word: Suffered? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That all the time He lived on earth, but especially at the end of His life, He bore, in body and soul, the wrath of God against the sin of the whole human race; in order that by His passion, as the only propitiatory sacrifice, He might redeem our body and soul from everlasting damnation, and obtain for us the grace of God, righteousness, and eternal life.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='38' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 38. Why did He suffer under Pontius Pilate, as judge?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That He, being innocent, might be condemned by the temporal judge, and thereby deliver us from the severe judgment of God, to which we are exposed. 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='39'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 39. Is there anything more in His having been crucified, than if He had died some other death? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Yes: for thereby I am assured, that He took on Himself the curse which lay upon me; because the death of the cross was accursed of God. 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='40' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>40. Why was it necessary for Christ to suffer death?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Because, by reason of the justice and truth of God, satisfaction for our sins could be made no otherwise than by the death of the Son of God.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='41'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 41. Why was He buried? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          To show thereby that He was really dead.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='42' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>42. Since then Christ died for us, why must we also die? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Our death is not a satisfaction for our sin, but only a dying to sins and entering into eternal life.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='43'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>43. What further benefit do we receive from the sacrifice and death of Christ on the cross?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That by His power our old man is with Him crucified, slain and buried; that so the evil lusts of the flesh may no more reign in us, but that we may offer ourselves unto Him a sacrifice of thanksgiving.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='44' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>44. Why is it added: He descended into Hell?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That in my greatest temptations I may be assured that Christ, my Lord, by His inexpressible anguish, pains and terrors, which He suffered in His soul on the cross and before, has redeemed me from the anguish and torment of hell.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='45'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>45. What benefit do we receive from the Resurrection of Christ?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          First, by His resurrection He has overcome death, that He might make us partakers of the righteousness which by His death He has obtained for us. Secondly, we also are now by His power raised up to a new life. Thirdly, the resurrection of Christ is to us a sure pledge of our blessed resurrection.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='46' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>46. How dost thou understand the words: He ascended into Heaven? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That Christ, in sight of His disciples, was taken up from the earth into heaven; and in our behalf there continues, until He shall come again to judge the living and the dead.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='47'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>47. Is not then Christ with us even unto the end of the world, as He has promised? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Christ is true Man and true God: according to His human nature, He is now not on earth; but according to His Godhead, majesty, grace, and Spirit, He is at no time absent from us.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='48' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>48. But are not, in this way, the two natures in Christ separated from one another, if the Manhood be not wherever the Godhead is? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          By no means; for since the Godhead is incomprehensible and everywhere present, it must follow that it is indeed beyond the bounds of the Manhood, which it has assumed, but is yet nonetheless in the same also, and remains personally united to it.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='49'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>49. What benefit do we receive from Christ’s ascension into heaven?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          First, that He is our Advocate in the presence of His Father in heaven. Secondly, that we have our flesh in heaven, as a sure pledge, that He, as the Head, will also take us, His members, up to Himself. Thirdly, that He sends us His Spirit, as an earnest, by whose power we seek those things which are above, where Christ sitteth on the right hand of God, and not things on the earth.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='50' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>50. Why is it added: And sitteth at the right hand of God? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Because Christ ascended into heaven for this end, that He might there appear as Head of His Church, by whom the Father governs all things.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='51'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>51. What benefit do we receive from this glory of our Head, Christ? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          First, that by His Holy Spirit He sheds forth heavenly gifts in us, His members; then, that by His power He defends and preserves us against all enemies.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='52' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>52. What comfort is it to thee, that Christ shall come again to judge the quick and the dead?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That in all my sorrows and persecutions, with uplifted head, I look for the selfsame One, who has before offered Himself for me to the judgment of God and removed from me all curse, to come again as Judge from heaven; who shall cast all His and my enemies into everlasting condemnation, but shall take me, with all His chosen ones, to Himself into heavenly joy and glory.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='53'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>53. What dost thou believe concerning the Holy Ghost?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          First, that He is co-eternal God with the Father and the Son. Secondly, that He is also given unto me; makes me by a true faith partaker of Christ and all His benefits; comforts me; and shall abide with me forever.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='54' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>54. What dost thou believe concerning the Holy Catholic Church?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That, out of the whole human race, from the beginning to the end of the world, the Son of God, by His Spirit and Word, gathers, defends and preserves for Himself unto everlasting life, a chosen communion, in the unity of the true faith; and that I am, and forever shall remain, a living member of the same.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='55'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>55. What dost thou understand by the Communion of Saints?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          First, that believers, all and every one, as members of Christ have part in Him and in all His treasures and gifts; secondly, that each one must feel himself bound to use his gifts, readily and cheerfully, for the advantage and welfare of other members.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='56' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>56. What dost thou believe concerning the Forgiveness of Sins?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That God, for the sake of Christ’s satisfaction, will no more remember my sins, neither the sinful nature with which I have to struggle all my life long; but graciously imputes to me the righteousness of Christ, that I may nevermore come into condemnation.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='57'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>57. What comfort does the Resurrection of the Body afford thee?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That not only my soul, after this life, shall be immediately taken up to Christ its Head; but also that this my body, raised by the power of Christ, shall again be united with my soul, and made like unto the glorious body of Christ.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='58' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>58. What comfort hast thou from the article of the Life Everlasting?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That, inasmuch as I now feel in my heart the beginning of eternal joy, I shall after this life possess complete bliss, such as eye hath not seen, nor ear heard, neither hath entered into the heart of man; therein to praise God for ever.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='59'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>59. But what does it help thee now, that thou believest all this?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That I am righteous in Christ before God, and an heir of eternal life.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='60' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>60. How art thou righteous before God?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Only by true faith in Jesus Christ. That is: although my conscience accuse me, that I have grievously sinned against all the commandments of God, and have never kept any of them, and that I am still prone always to all evil, yet God, without any merit of mine, of mere grace, grants and imputes to me the perfect satisfaction, righteousness and holiness of Christ, as if I had never committed nor had any sin, and had myself accomplished all the obedience which Christ has fulfilled for me, if only I accept such benefit with a believing heart.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='61'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>61. Why sayest thou, that thou art righteous only by faith?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Not that I am acceptable to God on account of the worthiness of my faith; but because only the satisfaction, righteousness and holiness of Christ is my righteousness before God, and I can receive the same and make it my own in no other way than by faith only.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='62' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>62. But why cannot our good works be the whole or part of our righteousness before God?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Because the righteousness which can stand before the judgment-seat of God must be perfect throughout and wholly conformable to the divine law; whereas even our best works in this life are all imperfect and defiled with sin.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='63'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>63. How is it that our good works merit nothing, while yet it is God’s will to reward them in this life and in that which is to come? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          The reward comes not of merit, but of grace.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='64' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>64. But does not this doctrine make men careless and profane? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No, for it is impossible that those who are implanted into Christ by true faith, should not bring forth fruits of thankfulness.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='65'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>65. Since then we are made partakers of Christ and all his benefits by faith only, whence comes this faith?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          The Holy Ghost works it in our hearts by the preaching of the Gospel, and confirms it by the use of the Holy Sacraments.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='66' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>66. What are the Sacraments? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          The Sacraments are visible, holy signs and seals, appointed by God for this end, that by the use thereof He may the more fully declare and seal to us the promise of the Gospel: namely, that He grants us out of free grace the forgiveness of sins and everlasting life, for the sake of the one sacrifice of Christ accomplished on the cross.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='67'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>67. Are both these, then, the Word and the Sacraments, designed to direct our faith to the sacrifice of Jesus Christ on the cross, as the only ground of our salvation?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Yes truly; for the Holy Ghost teaches in the Gospel, and by the Holy Sacraments assures us, that our whole salvation stands in the one sacrifice of Christ made for us on the cross.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='68' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>68. How many Sacraments has Christ appointed in the New Testament?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Two: Holy Baptism and the Holy Supper.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='69'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>69. How is it signified and sealed unto thee in Holy Baptism, that thou has part in the one sacrifice of Christ on the cross? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Thus: that Christ has appointed this outward washing with water, and has joined therewith this promise, that I am washed with His blood and Spirit from the pollution of my soul, that is, from all my sins, as certainly, as I am washed outwardly with water, whereby commonly the filthiness of the body is taken away.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='70' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>70. What is it to be washed with the blood and Spirit of Christ? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          It is to have the forgiveness of sins from God, through grace, for the sake of Christ’s blood, which He shed for us in His sacrifice on the cross; and also, to be renewed by the Holy Ghost, and sanctified to be members of Christ, that so we may more and more die unto sin, and lead holy and unblamable lives.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='71'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>71. Where has Christ promised that we are as certainly washed with His blood and Spirit as with the water of Baptism? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          In the institution of Baptism, which runs thus: Go ye, therefore, and teach all nations, baptizing them in the name of the Father, and of the Son, and of the Holy Ghost. He that believeth and is baptized shall be saved; but he that believeth not shall be damned. This promise is also repeated where the Scripture calls Baptism the washing of regeneration and the washing away of sins.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='72' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>72. Is then the outward washing with water itself the washing away of sins?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No; for only the blood of Jesus Christ and the Holy Spirit cleanse us from all sin.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='73'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>73. Why, then, doth the Holy Ghost call Baptism the washing of regeneration, and the washing away of sins? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          God speaks thus not without great cause: namely, not only to teach us thereby that like as the filthiness of the body is taken away by water, so our sins also are taken away by the blood and Spirit of Christ; but much more, that by this divine pledge and token He may assure us, that we are as really washed from our sins spiritually, as our bodies are washed with water.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='74' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>74. Are infants also to be baptized?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Yes. For since they, as well as their parents, belong to the covenant and people of God, and both redemption from sin and the Holy Ghost, who works faith, are through the blood of Christ promised to them no less than to their parents: they are also by Baptism, as a sign of the covenant, to be ingrafted into the Christian Church, and distinguished from the children of unbelievers, as was done in the Old Testament by Circumcision, in place of which in the New Testament Baptism is appointed.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='75'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>75. How is it signified and sealed unto thee in the Holy Supper that thou dost partake of the one sacrifice of Christ on the cross and all His benefits?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Thus; that Christ has commanded me and all believers to eat of this broken bread, and to drink of this cup, and has joined therewith these promises: First, that His body was offered, and broken on the cross for me, and His blood shed for me, as certainly as I see with my eyes the bread of the Lord broken for me, and the cup communicated to me; and further, that, with His crucified body and shed blood, He Himself feeds and nourishes my soul to everlasting life as certainly as I receive from the hand of the minister, and taste with my mouth, the bread and cup of the Lord, which are given me as certain tokens of the body and blood of Christ.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='76' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>76. What is it to eat the crucified body and drink the shed blood of Christ? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          It is not only to embrace with a believing heart all the suffering and death of Christ, and thereby to obtain the forgiveness of sins and eternal life; but moreover also, to be so united more and more to His sacred body by the Holy Ghost, who dwells both in Christ and in us, that although He is in heaven, and we on the earth, we are nevertheless flesh of His flesh and bone of His bones, and live and are governed for ever by one Spirit, as members of the same body are by one soul.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='77'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>77. Where has Christ promised that He will thus feed and nourish believers with His body and blood, as certainly as they eat of this broken bread and drink of this cup?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          In the institution of the Supper, which runs thus: The Lord Jesus Christ, the same night in which he was betrayed, took bread; and when He had given thanks, He brake it, and said: Take, eat, this is My body, which is broken for you; this do in remembrance of Me. After the same manner also He took the cup, when he had supped, saying: This cup is the New Testament in My blood: This do ye as often as ye drink it, in remembrance of Me. For as often as ye eat this bread, and drink this cup, ye do show the Lord’s death till He come.<p />
          And this promise is repeated also by St. Paul, where he says: The cup of blessing which we bless, is it not the communion of the blood of Christ? The bread which we break, is it not the communion of the body of Christ? For we, being many, are one bread, and one body; for we are all partakers of that one bread.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='78' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 78. Do then the bread and wine become the real body and blood of Christ? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No: but as the water, in Baptism, is not changed into the blood of Christ, nor becomes the washing away of sins itself, being only the divine token and assurance thereof, so also, in the Lord’s Supper, the sacred bread does not become the body of Christ itself, though agreeably to the nature and usage of sacraments it is called the body of Christ.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='79'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 79. Why then doth Christ call the bread His body, and the cup His blood, or the New Testament in His blood; and St. Paul, the communion of the body and blood of Christ? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Christ speaks thus not without great cause: namely, not only to teach us thereby, that, like as the bread and wine sustain this temporal life, so also His crucified body and shed blood are the true meat and drink of our souls unto life eternal; but much more, by this visible sign and pledge to assure us, that we are as really partakers of His true body and blood, through the working of the Holy Ghost, as we receive by the mouth of the body these holy tokens in remembrance of Him; and that all His sufferings and obedience are as certainly our own, as if we had ourselves suffered and done all in our own person.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='80' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>80. What difference is there between the Lord’s Supper and the Popish Mass? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          The Lord’s Supper testifies to us, that we have full forgiveness of all our sins by the one sacrifice of Jesus Christ, which He Himself has once accomplished on the cross; and that by the Holy Ghost we are ingrafted into Christ, who with His true body is now in heaven at the right hand of the Father, and is to be there worshiped. But the Mass teaches, that the living and the dead have not forgiveness of sins through the sufferings of Christ, unless Christ is still daily offered for them by the priests; and that Christ is bodily under the form of bread and wine, and is therefore to be worshiped in them. And thus the Mass at bottom is nothing else than a denial of the one sacrifice and passion of Jesus Christ, and an accursed idolatry.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='81'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>81. Who are to come unto the table of the Lord? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Those who are displeased with themselves for their sins, yet trust that these are forgiven them, and that their remaining infirmity is covered by the passion and death of Christ; who also desire more and more to strengthen their faith and amend their life. But the impenitent and hypocrites eat and drink judgment to themselves.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='82' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>82. Are they then also to be admitted to this Supper, who show themselves to be, by their confession and life, unbelieving and ungodly? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No: for by this the covenant of God is profaned, and His wrath provoked against the whole congregation; wherefore the Christian Church is bound, according to the order of Christ and His Apostles, by the office of the keys to exclude such persons, until they amend their life.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='83'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 83. What is the Office of the Keys? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          The Preaching of the Holy Gospel and Church Discipline; by which two things the kingdom of heaven is opened to believers and shut against unbelievers.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='84' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>84. How is the kingdom of heaven opened and shut by the Preaching of the Holy Gospel? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          In this way: that according to the command of Christ, it is proclaimed and openly witnessed to believers, one and all, that as often as they accept with true faith the promise of the Gospel, all their sins are really forgiven them of God for the sake of Christ’s merits; and on the contrary, to all unbelievers and hypocrites, that the wrath of God and eternal condemnation abide on them, so long as they are not converted; according to which witness of the Gospel, will be the judgment of God both in this life and in that which is to come.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='85'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>85. How is the kingdom of heaven shut and opened by Church Discipline? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          In this way: that according to the command of Christ, if any under the Christian name show themselves unsound either in doctrine or life, and after repeated brotherly admonition refuse to turn from their errors of evil ways, they are complained of to the church or to its proper officers, and, if they neglect to hear them also, are by them excluded from the Holy Sacraments and the Christian communion, and by God Himself from the kingdom of Christ; and if they promise and show real amendment, they are again received as members of Christ and His Church.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='86' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>86. Since then we are redeemed from our misery by grace through Christ, without any merit of ours, why must we do good works? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Because Christ, having redeemed us by His blood, renews us also by His Holy Spirit after His own image, that with our whole life we may show ourselves thankful to God for His blessing, and that He may be glorified through us; then also, that we ourselves may be assured of our faith by the fruits thereof, and by our godly walk may win others also to Christ.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='87'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>87. Can they then be saved who do not turn to God from their unthankful, impenitent life?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          By no means: for, as the Scripture saith, no unchaste person, idolater, adulterer, thief, covetous man, drunkard, slanderer, robber, or any such like, shall inherit the kingdom of God.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='88' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>88. In how many things does true repentance or conversion consist? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          In two things: the dying of the old man, and the quickening of the new.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='89'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>89. What is the dying of the old man? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Heartfelt sorrow for sin; causing us to hate and turn from it always more and more.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='90' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>90. What is the quickening of the new man?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Heartfelt joy in God; causing us to take delight in living according to the will of God in all good works.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='91'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>91. But what are good works?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Those only which are done from true faith, according to the Law of God, for His glory; and not such as rest on our own opinion, or the commandments of men.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='92' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>92. What is the Law of God?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h5>God spake all these words, saying:</h5>
          <h4>
          FIRST COMMANDMENT
          </h4>
          <h5>I am the Lord thy God, which have brought thee out of the land of Egypt, out of the house of bondage. Thou shalt have no other gods before Me.</h5>
          <h4>SECOND COMMANDMENT</h4>
          <h5>Thou shalt not make unto thee any graven image, or any likeness of anything that is in heaven above or that is in the earth beneath, or that is in the water under the earth; thou shalt not bow down thyself to them, nor serve them. For I the Lord thy God am a jealous God, visiting the iniquity of the fathers upon the children unto the third and fourth generation of them that hate Me; and showing mercy unto thousands of them that love Me, and keep My commandments. </h5>
          <h4>THIRD COMMANDMENT</h4>
          <h5>Thou shalt not take the name of the Lord thy God in vain: for the Lord will not hold him guiltless that taketh His name in vain.</h5>
          <h4>FOURTH COMMANDMENT</h4>
          <h5>Remember the Sabbath day to keep it holy. Six days shalt thou labor, and do all thy work: but the seventh day is the Sabbath of the Lord thy God; in it thou shalt not do any work, thou, nor thy son, nor thy daughter, thy manservant, nor thy maidservant, nor thy cattle, nor thy stranger that is within thy gates. For in six days the Lord made heaven and earth, the sea, and all that in them is, and rested the seventh day: wherefore the Lord blessed the Sabbath day, and hallowed it.</h5>
          <h4>FIFTH COMMANDMENT</h4>
          <h5>Honor thy father and thy mother; that thy days may be long upon the land which the Lord thy God giveth thee.</h5>
          <h4>SIXTH COMMANDMENT</h4>
          <h5>Thou shalt not kill.</h5>
          <h4>SEVENTH COMMANDMENT</h4>
          <h5>Thou shalt not commit adultery.</h5>
          <h4>EIGHTH COMMANDMENT</h4>
          <h5>Thou shalt not steal.</h5>
          <h4>NINTH COMMANDMENT</h4>
          <h5>Thou shalt not bear false witness against thy neighbor.</h5>
          <h4>TENTH COMMANDMENT</h4>
          <h5>Thou shalt not covet thy neighbor’s house; thou shalt not covet thy neighbor’s wife, nor his manservant, nor his maidservant, nor his ox, nor his ass, nor anything that is thy neighbor’s.</h5>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='93'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>93. How are these commandments divided? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Into two tables: the first of which teaches us, in four commandments, what duties we owe to God; the second, in six, what duties we owe to our neighbor.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='94' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>94. What does God require in the first commandment? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That, on peril of my soul’s salvation, I avoid and flee all idolatry, sorcery, enchantments, invocation of saints or of other creatures; and that I rightly acknowledge the only true God, trust in Him alone, with all humility and patience expect all good from Him only, and love, fear and honor Him with my whole heart; so as rather to renounce all creatures than do the least thing against His will.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='95'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>95. What is idolatry? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          It is instead of the one true God who has revealed Himself in His Word, or along with the same, to conceive or have something else on which to place our trust.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='96' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>96. What does God require in the second commandment?  </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That we in no wise make any image of God, nor worship Him in any other way than He has commanded in His Word.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='97'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>97. Must we then not make any image at all? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          God may not and cannot be imaged in any way; as for creatures, though they may indeed be imaged, yet God forbids the making or keeping any likeness of them, either to worship them, or by them to serve Himself.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='98' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>98. But may not pictures be tolerated in churches as books for the laity? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No: for we should not be wiser than God, who will not have His people taught by dumb idols, but by the lively preaching of His Word.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='99'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 99. What is required in the third commandment?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That we must not by cursing, or by false swearing, nor yet by unnecessary oaths, profane or abuse the name of God; nor even by our silence and connivance be partakers of these horrible sins in others; and in sum, that we use the holy name of God no otherwise than with fear and reverence, so that He may be rightly confessed and worshiped by us, and be glorified in all our words and works.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='100' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 100. Is then the profaning of God’s name by swearing and cursing so grievous a sin that His wrath is kindled against those also who seek not, as much as in them lies, to hinder and forbid the same?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Yes truly: for no sin is greater, or more provoking to God than the profaning of His name. Wherefore He even commanded it to be punished with death.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='101'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
       <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>101. But may we not swear by the name of God in a religious manner? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Yes; when the magistrate requires it, or it may be needful otherwise to maintain and promote fidelity and truth, to the glory of God and our neighbor’s good. For such swearing is grounded in God’s Word, and therefore was rightly used by the saints in the Old and New Testaments.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='102' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>102. May we swear by the saints or any other creature? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No: for a lawful oath is a calling upon God, as the only searcher of hearts, to bear witness to the truth, and to punish me if I swear falsely; which honor is due no creature.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='103'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 103. What does God require in the fourth commandment?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          In the first place, that the ministry of the Gospel and schools be maintained; and that I, especially on the day of rest, diligently attend church to learn the Word of God, to use the Holy Sacraments, to call publicly upon the Lord, and to give Christian alms. In the second place, that all the days of my life I rest from my evil works, allow the Lord to work in me by His Spirit, and thus begin in this life the everlasting Sabbath.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='104' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>104. What does God require in the fifth commandment? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That I show all honor, love and faithfulness to my father and mother, and to all in authority over me; submit myself with due obedience to all their good instruction and correction; and also bear patiently with their infirmities: since it is God’s will to govern us by their hand. 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='105'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>105. What does God require in the sixth commandment? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That I neither in thought, nor in word or look, much less in deed, revile, hate, insult or kill my neighbor, whether by myself or by another; but lay aside all desire of revenge; moreover, that I harm not myself, nor wilfully run into any danger. Wherefore also, to restrain murder, the magistrate is armed with the sword. 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='106' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>106. But this commandment speaks only of killing? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          In forbidding this, however, God means to teach us that He abhors the root of murder, namely, envy, hatred, anger, and desire of revenge; and that all these are in His sight hidden murder.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='107'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>107. Is it then enough that we do not kill our neighbor in any such way? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No: for in condemning envy, hatred, and anger, God requires us to love our neighbor as ourselves, to show patience, peace, meekness, mercy and kindness towards him, and, so far as we have power, to prevent his hurt; also to do good even unto our enemies. 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='108' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>108. What does the seventh commandment teach us? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That all unchastity is accursed of God; and that we should therefore loathe it from the heart, and live chastely and modestly whether in holy wedlock or single life.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='109' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>109. Does God in this commandment forbid nothing more than adultery and such like gross sins? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Since our body and soul are both temples of the Holy Ghost, it is His will that we keep both pure and holy; for which reason He forbids all unchaste actions, gestures, words, thoughts, desires, and whatever may entice thereto.
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='110' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>110. What does God forbid in the eighth commandment? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Not only such theft and robbery as are punished by the magistrate; but God views as theft all wicked tricks and devices, whereby we seek to draw to ourselves our neighbor’s goods, whether by force or with show of right, such as unjust weights, ells, measures, wares, coins, usury, or any means forbidden of God; so moreover all covetousness, and all useless waste of His gifts. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='111' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>111. But what does God require of thee in this commandment? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That I further my neighbor’s good, where I can and may; deal with him as I would have others deal with me; and labor faithfully, that I may be able to help the poor in their need. 

          </h4>
        </b-col>
      </b-row>
      
    </b-container>
    
    <b-container fluid  id='112' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 112. What is required in the ninth commandment? </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That I bear false witness against no one; wrest no one’s words; be no backbiter, or slanderer; join in condemning no one unheard and rashly; but that I avoid, on pain of God’s heavy wrath, all lying and deceit, as being the proper works of the devil; in matters of judgment and justice and in all other affairs love, honestly speak and confess the truth; and, so far as I can, defend and promote my neighbor’s good name. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid   id='113' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>113. What is required in the tenth commandment? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That not even the least inclination or thought against any of God’s commandments ever enter into our heart; but that, with our whole heart, we continually hate all sin, and take pleasure in all righteousness. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='114' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>114. Can those who are converted to God keep these commandments perfectly? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          No: but even the holiest men, while in this life, have only a small beginning of this obedience; yet so, that with earnest purpose they begin to live, not only according to some, but according to all the commandments of God. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='115'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>115. Why then doth God so strictly enjoin upon us the ten commandments, since in this life no one can keep them? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          First, that all our life long, we may learn more and more to know our sinful nature, and so the more earnestly seek forgiveness of sins and righteousness in Christ; secondly, that we may continually strive, and beg from God the grace of the Holy Ghost, so as to become more and more changed into the image of God, till we attain finally to full perfection after this life. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='116' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>116. Why is Prayer necessary for Christians? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Because it is the chief part of the thankfulness which God requires of us; and because God will give His grace and Holy Spirit only to such, as earnestly and without ceasing, beg them from Him, and render thanks unto Him for them. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='117'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>117. What belongs to such prayer, as God is pleased with and will hear? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          First, that from the heart we call only upon the one true God, who has revealed Himself to us in His word, for all that He has commanded us to ask of Him; secondly, that we thoroughly know our need and misery, so as to humble ourselves before the face of His Divine Majesty; thirdly, that we be firmly assured, that withstanding our unworthiness He will, for the sake of Christ our Lord, certainly hear our prayer, as He has promised us in His word. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='118' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 118. What has God commanded us to ask of Him? 
</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          All things necessary for soul and body, which Christ our Lord has comprised in the prayer taught us by Himself. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='119'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>119. What is the Lord’s Prayer? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Our Father which art in heaven: Hallowed by Thy name. Thy kingdom come. Thy will be done in earth, as it is in heaven. Give us this day our daily bread. And forgive us our debts, as we forgive our debtors. And lead us not into temptation; but deliver us from evil. For Thine is the kingdom, and the power, and the glory, for ever. Amen. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='120' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>120. Why has Christ commanded us to address God thus: Our Father? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          To awaken in us, at the very beginning of our prayer, that filial reverence and trust toward God, which are to be the ground of our prayer; namely, that God has become our Father through Christ, and will much less deny us what we ask of Him in faith, than our parents refuse us earthly things. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='121'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 121. Why is it added: Who art in heaven? 
</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          That we may have no earthly thought of the heavenly majesty of God; and may expect from His almighty power all things necessary for body and soul. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='122' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>122. What is the first petition? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Hallowed be Thy name. That is: Enable us rightly to know Thee, and to hallow, magnify and praise Thee in all Thy works, in which shine forth Thy power, wisdom, goodness, justice, mercy and truth; and likewise so to order our whole life, in thought, word and work, that Thy name may not be blasphemed, but honored and praised on our account. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='123'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>123. What is the second petition? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Thy kingdom come. That is: So govern us by Thy word and Spirit, that we submit ourselves unto Thee always more and more; preserve and increase Thy Church; destroy the works of the devil, every power that exalteth itself against Thee, and all wicked devices formed against Thy holy word, until the full coming of Thy kingdom, wherein Thou shalt be all in all. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='124' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>124. What is the third petition? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Thy will be done in earth, as it is in heaven. That is: Grant that we and all men may renounce our own will, and yield ourselves without gainsaying, to Thy will which alone is good; that so every one may fulfill his office and calling, as willingly and truly as the angels do in heaven. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='125'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>125. What is the fourth petition? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Give us this day our daily bread. That is: Be pleased to provide for all our bodily need; that we may thereby know that Thou art the only fountain of all good, and that without Thy blessing, neither our care and labor, nor Thy gifts can profit us; and may therefore withdraw our trust from all creatures, and place it alone in Thee. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='126' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>126. What is the fifth petition? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          And forgive us our debts as we forgive our debtors. That is: Be pleased for the sake of Christ’s blood, not to impute to us, miserable sinners, our manifold transgressions, nor the evil which still always cleaves to us, as we find this witness of Thy grace in us, that it is our full purpose heartily to forgive our neighbor. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='127'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 127. What is the sixth petition? 
</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          And lead us not into temptation; but deliver us from evil. That is: Since we are so weak in ourselves, that we cannot stand a moment; while our deadly enemies, the devil, the world and our own flesh, assail us without ceasing; be pleased to preserve and strengthen us by the power of Thy Holy Spirit, that we may make firm stand against them, and not sink in this spiritual war, until we come off at last with complete victory. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='128' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>128. How do you close this prayer? 
 </b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          For Thine is the kingdom, and the power, and the glory, for ever. That is: All this we ask of Thee, because as our King, having power over all things, Thou art both willing and able to give us all good; and that thereby not we, but Thy holy Name may be glorified for ever. 

          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='129'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b> 129. What is the meaning of the word Amen? 
</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          Amen means: So shall it truly and surely be. For my prayer is much more certainly heard of God, than I feel in my heart that I desire these things of Him.

          </h4>
        </b-col>
      </b-row>
    </b-container>
    </div>
    </b-col>
    </b-row>
    </b-container>

    <b-container fluid class='blue' style="padding-top:25px; padding-bottom:25px">
      <b-row >
        <b-col sm='4' offset-sm='4'>
          <a href='https://github.com/cwoo107/heidelberg_catechism' ><unicon name="github-alt" fill='white' height="50" width="50" /></a>
          <!--<a href='https://vuejs.org' ><unicon name="vuejs-alt" fill='white' height="50" width="50"  /></a>-->
        </b-col>
      </b-row>
    </b-container>

  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #1F1A19;
  margin-top:-50px;
  transition-duration: 0.3s;
  transition-property: opacity;
  transition-timing-function: ease;
  
}

.blue {
  background: #1A1F23;
  color: #EAEAEB;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #858170 !important;
}
img {
  max-width: 65%;
    
}
</style>
