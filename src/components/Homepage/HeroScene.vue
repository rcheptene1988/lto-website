<template>
    <div>
        <!-- Hero Section -->
        <section class="section hero_scene">
            <div class="container" id="home">
            <div class="row">
                <div class="heading col-12 col-md-7 offset-md-1">
                <h1>Staking made easy</h1>
                <div class="subtitle">
                    <p>
                    Stake your crypto with us and secure the network of your choice. Earn
                    staking rewards.
                    </p>
                </div>
                <a class="btn scroll" href="#networks">Stake now</a>
                </div>
                <div class="col-12 col-md-4">
                <div class="image-wrap">
                    <img src="/dist/img/man-4.png" alt="" />
                </div>
                </div>
            </div>
            <div class="row stats">
                <div class="col-12">
                <div class="header-stats">
                    <div class="header-stats-item">
                    <div class="total-assets-staked">Total assets staked:</div>
                    <div class="big-numbers" id="assets_count">
                        $920814.71<!-- ${{ $store.state.leasing.totalStaked }} -->
                    </div>
                    </div>
                    <div class="header-stats-item">
                    <div class="total-assets-staked">Stakers:</div>
                    <div class="big-numbers" id="stakers_count">
                        56 <!-- {{ $store.state.leasing.stakers }} -->
                    </div>
                    </div>
                </div>
                </div>
            </div>
            </div>
        </section>
    </div>
</template>

<script>

export default {
  name: "HeroScene",
  computed: {},
  methods: {},
};

</script>