<!--
  - This file is part of Solana Reference Stake Pool code.
  -
  - Copyright © 2021, mFactory GmbH
  -
  - Solana Reference Stake Pool is free software: you can redistribute it
  - and/or modify it under the terms of the GNU Affero General Public License
  - as published by the Free Software Foundation, either version 3
  - of the License, or (at your option) any later version.
  -
  - Solana Reference Stake Pool is distributed in the hope that it
  - will be useful, but WITHOUT ANY WARRANTY; without even the implied
  - warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
  - See the GNU Affero General Public License for more details.
  -
  - You should have received a copy of the GNU Affero General Public License
  - along with this program.
  - If not, see <https://www.gnu.org/licenses/agpl-3.0.html>.
  -
  - You can be released from the requirements of the Affero GNU General Public License
  - by purchasing a commercial license. The purchase of such a license is
  - mandatory as soon as you develop commercial activities using the
  - Solana Reference Stake Pool code without disclosing the source code of
  - your own applications.
  -
  - The developer of this program can be contacted at <info@mfactory.ch>.
  -->

<script setup lang="ts">
</script>

<template>
  <q-header :class="!$q.dark.isActive ? 'bg-white text-dark' : null" class="app-header">
    <div class="container">
      <q-toolbar>
        <router-link class="app-header__logo" to="/" :style="{ 'text-decoration': 'none' }">
          <div style="display:flex;align-items: center;">
            <img alt="app-logo" src="@/assets/img/customize/app-logo.png" class="image-logo">
            <div>
              <span class="block text-white symbol">ESG</span>
              <span class="block text-no-wrap text-white group-name">ecoToken Stake Group</span>
            </div>
          </div>
        </router-link>
        <div class="xs-hide">
          <stacked-and-liquidity />
        </div>
        <q-space />
        <div class="app-header__epoch">
          <epoch />
        </div>
        <q-space />
        <div class="text-right">
          <div class="q-gutter-sm justify-end flex wrap">
            <cluster-selector />
            <connect-wallet />
          </div>
        </div>
      </q-toolbar>
    </div>
  </q-header>
</template>

<style scoped>
    .image-logo {
        width:64px;
        height:64px;
        margin-right:16px;
    }
    .symbol {
        font-size: 48px;
        line-height: 42px;
    }
    .group-name {
        font-size: 12px;
    }
</style>
