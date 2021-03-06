---
title: Taproot

## Required.  At least one category to which this topic belongs.  See
## schema for options
categories:
  - Soft Forks
  - Scripts and Addresses
  - Privacy Enhancements

## Required.  Use Markdown formatting.  Only one paragraph.  No links allowed.
excerpt: >
  **Taproot** is a proposed soft fork change to Bitcoin that will allow
  payments to schnorr public keys that may optionally commit to a script
  that can be revealed at spend time.

## Optional.  Use Markdown formatting.  Multiple paragraphs.  Links allowed.
extended_summary: |
  Coins protected by taproot may be spent either by satisfying one of
  the committed scripts or by simply providing a signature that verifies
  against the public key (allowing the script to be kept private).
  Taproot is intended for use with schnorr signatures that simplify
  multiparty construction (e.g. using [MuSig][]) and with MAST to
  allow committing to more than one script, any one of which may be
  used at spend time.

## Optional
primary_sources:
    - title: Original description
      link: https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2018-January/015614.html
    - title: bip-taproot
    - title: Draft implementation
      link: https://github.com/sipa/bitcoin/commits/taproot

## Optional
optech_mentions:
  - title: Reducing taproot commitment size
    url: /en/newsletters/2019/05/29/#move-the-oddness-byte
    date: 2019-05-29

  - title: "Executive briefing: the next soft fork"
    url: /en/2019-exec-briefing/#the-next-softfork
    date: 2019-06-14
    feature: true

  - title: Overview of Taproot and Tapscript
    url: /en/newsletters/2019/05/14/#soft-fork-discussion
    date: 2019-05-14

  - title: Extended summary of bip-taproot and bip-tapscript
    url: /en/newsletters/2019/05/14/#overview-of-the-taproot--tapscript-proposed-bips
    date: 2019-05-14
    feature: true

  - title: Taproot (major developments of 2018, January)
    url: /en/newsletters/2018/12/28/#taproot
    date: 2018-12-28

  - title: What a taproot soft fork might look like
    url: /en/newsletters/2018/12/18/#description-about-what-might-be-included-in-a-schnorr-taproot-soft-fork
    date: 2018-12-18

  - title: "Suggested removal of P2SH address wrapper from taproot proposal"
    url: /en/newsletters/2019/09/25/#comment-if-you-expect-to-need-p2sh-wrapped-taproot-addresses
    date: 2019-09-25

  - title: Update on changes to schnorr, taproot, and tapscript
    url: /en/newsletters/2019/10/16/#taproot-update
    date: 2019-10-16

  - title: Announcement of structured taproot review
    url: /en/newsletters/2019/10/23/#taproot-review
    date: 2019-10-23

  - title: Bitcoin Optech schnorr/taproot workshop
    url: /en/schorr-taproot-workshop/
    date: 2019-10-29
    feature: true

  - title: Impact of bech32 length-change mutablity on v1 segwit script length
    url: /en/newsletters/2019/11/13/#taproot-review-discussion-and-related-information
    date: 2019-11-13

  - title: Blog post about x-only schnorr pubkeys
    url: /en/newsletters/2019/11/13/#x-only-pubkeys
    date: 2019-11-13

  - title: "2019 year-in-review: taproot"
    url: /en/newsletters/2019/12/28/#taproot
    date: 2019-12-28

  - title: Final organized review, presentation slides, and LN integration ideas
    url: /en/newsletters/2020/01/08/#final-week-of-organized-taproot-review
    date: 2020-01-08

  - title: btcdeb adds `tap` command for experimenting with taproot and tapscript
    url: /en/newsletters/2020/02/05/#taproot-and-tapscript-experimentation-tool
    date: 2020-02-05

  - title: Discussion about taproot versus alternatives
    url: /en/newsletters/2020/02/19/#discussion-about-taproot-versus-alternatives
    date: 2020-02-19

  - title: Taproot security from quantum computing threats
    url: /en/newsletters/2020/02/26/#could-taproot-create-larger-security-risks-or-hinder-future-protocol-adjustments-re-quantum-threats
    date: 2020-02-26

  - title: "Security analysis: taproot in the generic group model"
    url: /en/newsletters/2020/03/04/#taproot-in-the-generic-group-model
    date: 2020-03-04

  - title: Request for additional signature commitment to previous scriptPubKeys
    url: /en/newsletters/2020/05/13/#request-for-an-additional-taproot-signature-commitment
    date: 2020-05-13

  - title: "Request for comments on ammending BIP341 taproot transaction digest"
    url: /en/newsletters/2020/05/20/#evaluate-proposed-changes-to-bip341-taproot-transaction-digest
    date: 2020-05-28

  - title: Example sizes of multisig taproot transactions
    url: /en/newsletters/2020/05/27/#what-are-the-sizes-of-single-sig-and-2-of-3-multisig-taproot-inputs
    date: 2020-05-27

  - title: Taproot eliminates vulnerability related to segwit fee overpayment attack
    url: /en/newsletters/2020/06/10/#fee-overpayment-attack-on-multi-input-segwit-transactions
    date: 2020-06-10

  - title: BIP341 transaction digest amended with extra commitment to scriptPubKeys
    url: /en/newsletters/2020/06/10/#bips-920
    date: 2020-06-10

  - title: "Coinpool: using taproot to help create payment pools"
    url: /en/newsletters/2020/06/17/#coinpool-generalized-privacy-for-identifiable-onchain-protocols
    date: 2020-06-17

## Optional
see_also:
  - title: MAST
    link: topic mast
---
