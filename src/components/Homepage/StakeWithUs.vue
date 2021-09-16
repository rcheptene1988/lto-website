<template>
    <div>
        <!-- Section STAKE WITH US -->
        <section class="section coin-list" id="networks">
            <div class="container">
            <div class="heading">
                <h2>Stake with us</h2>
                <div class="subtitle">
                <p>We’re helping secure the following networks.</p>
                <p>Delegate your tokens and earn interest on your crypto.</p>
                </div>
            </div>
            <div class="row coin-list_row justify-content-md-center">
                <!-- <div class="col-6 col-md-3 coin-item-wrap">
                </div> -->
                <div class="col-6 col-md-3 coin-item-wrap">
                <div class="coin-item" onclick="location.href='https://lto.lease/lto'">
                    <div class="coin-item-inner">
                    <h4 class="name">LTO Network</h4>
                    <!-- <div class="rectangle"></div> -->
                    <div class="withlogo lto-logo-spec">
                        <img
                        class="lto-logo-spec-img"
                        alt="lto-network"
                        src="/dist/img/lto-full-logo.svg"
                        />
                    </div>
                    <div class="reward">
                        <p>Annual reward rate 6.8%<span id="ltoRoi"></span></p>
                    </div>
                    </div>
                    <a href="https://lto.lease/lto" class="coin-btn">Stake</a>
                </div>
                </div>
            </div>
            </div>
        </section>
    </div>
</template>

<script>

export default {
  name: "StakeWithUs",
  computed: {},
  methods: {},
};

</script>