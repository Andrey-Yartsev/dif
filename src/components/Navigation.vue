<template>
  <div class="navigation">
    <div class="top-message">
    Good morning, Alesha Tomkiewich
    Your last visit was on
    Fri Aug 25 2017 11:10 GMT+0300
    </div>
    <ul class="nav main-nav">
      <router-link tag="li" to="/">
        <svgicon name="accounts"></svgicon>
        Accounts
      </router-link>
      <router-link tag="li" to="/payments">
        <svgicon name="payments"></svgicon>
        Payments
      </router-link>
      <router-link tag="li" to="/e-wallet">
        <svgicon name="e-wallet"></svgicon>
        Kartiera E-Wallet
      </router-link>
      <router-link tag="li" to="/standing-orders">
        <svgicon name="calendar"></svgicon>
        Standing Orders
      </router-link>
      <router-link tag="li" to="/pending-transactions">
        <svgicon name="pending_transaction"></svgicon>
        Pending Transactions
      </router-link>
      <router-link tag="li" to="/internal-transfers">
        <svgicon name="internal_transfer"></svgicon>
        Internal Transfers
      </router-link>
      <router-link tag="li" to="/additional-account">
        <svgicon name="additional_acc"></svgicon>
        Open Additional Accounts
      </router-link>
      <router-link tag="li" to="/claim-funds">
        <svgicon name="claim_funds"></svgicon>
        Claim Funds
      </router-link>
      <router-link tag="li" to="/mailbox">
        <svgicon name="mailbox"></svgicon>
        Mailbox
      </router-link>
    </ul>
    <ul class="nav sub-nav">
      <router-link tag="li" to="/get-in-touch">
        Get In Touch
      </router-link>
      <router-link tag="li" to="/faq">
        FAQs
      </router-link>
      <router-link tag="li" to="/chat">
        Chat with us!
      </router-link>
      <router-link tag="li" to="/legal">
        Legal Information
      </router-link>
      <router-link tag="li" to="/charges">
        Transaction Charges
      </router-link>
      <router-link tag="li" to="/policy">
        Privacy Policy
      </router-link>
      <router-link tag="li" to="/feedback">
        Share Feedback
      </router-link>
    </ul>
  </div>
</template>

<script>
  import '@/components/icons/accounts'
  import '@/components/icons/payments'
  import '@/components/icons/e-wallet'
  import '@/components/icons/calendar'
  import '@/components/icons/pending_transaction'
  import '@/components/icons/internal_transfer'
  import '@/components/icons/additional_acc'
  import '@/components/icons/claim_funds'
  import '@/components/icons/mailbox'

  export default {
    name: 'navigation'
  }
</script>

<style lang="scss" scoped>
  @import "../styles/colors.scss";



</style>
