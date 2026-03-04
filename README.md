# Server Metrics 2026-03-04 07:41:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 37870.9 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417605
telemt_connections_bad_total 7132
telemt_handshake_timeouts_total 5996
telemt_upstream_connect_attempt_total 23833
telemt_upstream_connect_success_total 23721
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 23721
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 250
telemt_me_reconnect_attempts_total 4772
telemt_me_reconnect_success_total 4741
telemt_me_reader_eof_total 4851
telemt_me_idle_close_by_peer_total 4851
telemt_me_route_drop_no_conn_total 136756
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 797
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 498
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4851
telemt_me_writer_restored_same_endpoint_total 4720
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 348039
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 4092451068 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 104187884740 (97.03 GB)
telemt_user_unique_ips_current{user="hello"} 87
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 37865.1 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176092
telemt_connections_bad_total 1501
telemt_handshake_timeouts_total 23371
telemt_upstream_connect_attempt_total 77260
telemt_upstream_connect_success_total 76140
telemt_upstream_connect_fail_total 522
telemt_upstream_connect_attempts_per_request{bucket="1"} 76134
telemt_upstream_connect_attempts_per_request{bucket="2"} 528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 522
telemt_me_keepalive_timeout_total 1191
telemt_me_reconnect_attempts_total 44957
telemt_me_reconnect_success_total 44880
telemt_me_reader_eof_total 45980
telemt_me_idle_close_by_peer_total 45979
telemt_me_route_drop_no_conn_total 67215
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 355
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 236
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 46060
telemt_me_writer_restored_same_endpoint_total 44855
telemt_me_writer_removed_unexpected_minus_restored_total 1205
telemt_user_connections_total{user="hello"} 124208
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 1322357032 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 48409141124 (45.08 GB)
telemt_user_unique_ips_current{user="hello"} 54
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 37864.0 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349661
telemt_connections_bad_total 106747
telemt_handshake_timeouts_total 10439
telemt_upstream_connect_attempt_total 56949
telemt_upstream_connect_success_total 56619
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 56618
telemt_upstream_connect_attempts_per_request{bucket="2"} 157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24027
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 747
telemt_me_reconnect_attempts_total 25873
telemt_me_reconnect_success_total 25807
telemt_me_reader_eof_total 27204
telemt_me_idle_close_by_peer_total 27201
telemt_me_route_drop_no_conn_total 106027
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 531
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 331
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 199
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 27215
telemt_me_writer_restored_same_endpoint_total 25786
telemt_me_writer_removed_unexpected_minus_restored_total 1429
telemt_user_connections_total{user="hello"} 222832
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 2050884632 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 80278486644 (74.77 GB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 37862.9 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200440
telemt_connections_bad_total 16187
telemt_handshake_timeouts_total 7665
telemt_upstream_connect_attempt_total 29019
telemt_upstream_connect_success_total 28898
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 28898
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 6238
telemt_me_reconnect_success_total 6224
telemt_me_reader_eof_total 6343
telemt_me_idle_close_by_peer_total 6343
telemt_me_route_drop_no_conn_total 64836
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_pool_force_close_total 232
telemt_me_writer_removed_unexpected_total 6343
telemt_me_writer_restored_same_endpoint_total 6203
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 157797
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 1661014016 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 56268215828 (52.40 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 37861.5 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343746
telemt_connections_bad_total 6429
telemt_handshake_timeouts_total 130066
telemt_upstream_connect_attempt_total 53920
telemt_upstream_connect_success_total 53566
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 53566
telemt_upstream_connect_attempts_per_request{bucket="2"} 164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 728
telemt_me_reconnect_attempts_total 24984
telemt_me_reconnect_success_total 24965
telemt_me_reader_eof_total 26283
telemt_me_idle_close_by_peer_total 26282
telemt_me_route_drop_no_conn_total 94839
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 161
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 229
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 26295
telemt_me_writer_restored_same_endpoint_total 24940
telemt_me_writer_removed_unexpected_minus_restored_total 1355
telemt_user_connections_total{user="hello"} 200623
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 2567719620 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 46965741400 (43.74 GB)
telemt_user_unique_ips_current{user="hello"} 53
```