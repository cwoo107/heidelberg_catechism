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
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid   id='13' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='14' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='15'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='16' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='17'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='18' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='19'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='20' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='21'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='22' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='23'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='24' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='25'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='26' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='27'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='28' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='29'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='30' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='31'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='32' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='33'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='34' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 34. What is adoption?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
            A. Adoption is an act of God’s free grace,
          <a v-b-popover.click="'1 John 3:1'">
            [a]
          </a> 
           whereby we are received into the number, and have a right to all the privileges, of the sons of God.
          <a v-b-popover.click="'John 1:12; Rom. 8:17'">
            [b]
          </a> 
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='35'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='36' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='37'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='38' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='39'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='40' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='41'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='42' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='43'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='44' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='45'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='46' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='47'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='48' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='49'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='50' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='51'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='52' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='53'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='54' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='55'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='56' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='57'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='58' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='59'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='60' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='61'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='62' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='63'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='64' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='65'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='66' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='67'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='68' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='69'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='70' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='71'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='72' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='73'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='74' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='75'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='76' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='77'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='78' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='79'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='80' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='81'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='82' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='83'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='84' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='85'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='86' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='87'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='88' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='89'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='90' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='91'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='92' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='93'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='94' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='95'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='96' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='97'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='98' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='99'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='100' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='101'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
       <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='102' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='103'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='104' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='105'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='106' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='107'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='108' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='109' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='110' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='111' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
      
    </b-container>
    
    <b-container fluid  id='112' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid   id='113' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='114' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='115'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='116' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='117'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='118' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='119'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='120' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='121'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='122' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='123'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='124' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='125'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='126' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='127'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='128' class='blue' style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid  id='129'  style="padding-top:200px; padding-bottom:200px">
      <b-row >
        <b-col md='12' lg='4' offset-lg='1' style='display: flex; justify-content: center; flex-direction: column; padding-bottom:20px'>
          <h4><b>Q. 1. What is the chief end of man?</b></h4>
        </b-col>
        <b-col md='12' lg='4' offset-lg='2'>
          <h4>
          
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
