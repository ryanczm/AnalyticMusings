---
layout: post
title: Life Through A Factor Lens
category: quant
---

## Overview

In quant equity there are factors. The main purpose being to isolate out idiosyncratic return and do factor/performance attribution. I believe this framework is very useful when applied in a qualitative fashion to social science tasks. You're not doing any regression or matrix algebra in your head, you're just carefully examining effects and 'factors' or predictors and forming hypotheses carefully to quantify how factors contribute to the observed effect.

I was listening to Gappy's podcast on Corey Hoffstein's FWM and I'm not an equity quant but straightaway I thought of this.

## The Problem

We have some effect. We have a theory of what drivers or factors give this effect. And the effect is the sum of all the factor contributions. Viewing 'life through a factor (not volatility) lens' lets you:

* Be mindful of how the effect you observe can be sliced into individual contributions from each factor. 
* Check if factors which contribute to the effect are correlated; in other words now you need to be extra mindful or aware you cannot always isolate out the contribution of each factor.
* In life, I guess we don't care about idio returns. We care more about factor returns - inspecting, or understanding, the individual contribution each factor has on the observed effect.

With that, happy observing! This comes in quite useful in any social science task - investigating behavior.

## An Example

You might have $n$ humans (assets). You observe their returns in the cross section. You further observe or estimate their factor loadings matrix or exposures. This is the effect. You look at your factors that you think contribute and estimate a factor model in your head.

You want to see how much these effects come from factor A vs B vs C. You isolate out the A and C contributions via experiment (holding those constant) and with that perform an experiment to measure the factor contribution of B, knowing you isolated out/orthogonalized against A and C and don't need to worry about their effects.

## Factor Loadings

This is tricky as we know assets have factor 'loadings' or exposures. And the factor return stream is the 'pure' representation of that factor.

Well in a qualitative setting we don't care about loadings or exposures as we can't estimate the coefficients anyway. So it's fine G.

## Summary

In our problem, the qualitative setting, we don't care about:

* Factor loadings
* Idio return/risk

We care about

* Setting up careful experimnents to isolate out individual factor contributions amongst correlated factors
* Minimizing idio return (the effect not explained by your factor set) by getting more factors in - you have this large portion of the effect that cannot be explained by your existing factors. You need to figure out what's the missing factor! The goal, in this case, is to minimize alpha and replace it with beta.