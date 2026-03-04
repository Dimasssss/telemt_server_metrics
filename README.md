# Server Metrics 2026-03-04 06:04:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 32018.1 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257749
telemt_connections_bad_total 2436
telemt_handshake_timeouts_total 4930
telemt_upstream_connect_attempt_total 21524
telemt_upstream_connect_success_total 21425
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 21425
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 223
telemt_me_reconnect_attempts_total 4617
telemt_me_reconnect_success_total 4594
telemt_me_reader_eof_total 4700
telemt_me_idle_close_by_peer_total 4700
telemt_me_route_drop_no_conn_total 94583
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 673
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 420
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_me_writer_removed_unexpected_total 4700
telemt_me_writer_restored_same_endpoint_total 4574
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 243655
telemt_user_connections_current{user="hello"} 830
telemt_user_octets_from_client{user="hello"} 2586889216 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 78642625444 (73.24 GB)
telemt_user_unique_ips_current{user="hello"} 101
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 32014.9 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136528
telemt_connections_bad_total 427
telemt_handshake_timeouts_total 22070
telemt_upstream_connect_attempt_total 71242
telemt_upstream_connect_success_total 70385
telemt_upstream_connect_fail_total 412
telemt_upstream_connect_attempts_per_request{bucket="1"} 70379
telemt_upstream_connect_attempts_per_request{bucket="2"} 418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 412
telemt_me_keepalive_timeout_total 1041
telemt_me_reconnect_attempts_total 42633
telemt_me_reconnect_success_total 42604
telemt_me_reader_eof_total 43672
telemt_me_idle_close_by_peer_total 43671
telemt_me_route_drop_no_conn_total 42874
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 13
telemt_me_writer_removed_unexpected_total 43733
telemt_me_writer_restored_same_endpoint_total 42583
telemt_me_writer_removed_unexpected_minus_restored_total 1150
telemt_user_connections_total{user="hello"} 87995
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 793286672 (756.54 MB)
telemt_user_octets_to_client{user="hello"} 36455777864 (33.95 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 32013.5 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264031
telemt_connections_bad_total 91545
telemt_handshake_timeouts_total 5604
telemt_upstream_connect_attempt_total 43291
telemt_upstream_connect_success_total 43019
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 43019
telemt_upstream_connect_attempts_per_request{bucket="2"} 127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 560
telemt_me_reconnect_attempts_total 17781
telemt_me_reconnect_success_total 17734
telemt_me_reader_eof_total 18698
telemt_me_idle_close_by_peer_total 18695
telemt_me_route_drop_no_conn_total 58696
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 395
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 249
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 18706
telemt_me_writer_restored_same_endpoint_total 17713
telemt_me_writer_removed_unexpected_minus_restored_total 993
telemt_user_connections_total{user="hello"} 159120
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 1141440108 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 41649802412 (38.79 GB)
telemt_user_unique_ips_current{user="hello"} 70
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 32012.5 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136544
telemt_connections_bad_total 10911
telemt_handshake_timeouts_total 2752
telemt_upstream_connect_attempt_total 25097
telemt_upstream_connect_success_total 25006
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 25006
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 268
telemt_me_reconnect_attempts_total 5480
telemt_me_reconnect_success_total 5471
telemt_me_reader_eof_total 5567
telemt_me_idle_close_by_peer_total 5567
telemt_me_route_drop_no_conn_total 41030
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 135
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 141
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 5567
telemt_me_writer_restored_same_endpoint_total 5450
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 116112
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 1007716844 (961.03 MB)
telemt_user_octets_to_client{user="hello"} 43623178872 (40.63 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 32011.2 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280172
telemt_connections_bad_total 5507
telemt_handshake_timeouts_total 126184
telemt_upstream_connect_attempt_total 45514
telemt_upstream_connect_success_total 45195
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 45195
telemt_upstream_connect_attempts_per_request{bucket="2"} 150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 621
telemt_me_reconnect_attempts_total 21498
telemt_me_reconnect_success_total 21486
telemt_me_reader_eof_total 22670
telemt_me_idle_close_by_peer_total 22669
telemt_me_route_drop_no_conn_total 63704
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 202
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22683
telemt_me_writer_restored_same_endpoint_total 21461
telemt_me_writer_removed_unexpected_minus_restored_total 1222
telemt_user_connections_total{user="hello"} 143762
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 2023957172 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 33295226332 (31.01 GB)
telemt_user_unique_ips_current{user="hello"} 39
```