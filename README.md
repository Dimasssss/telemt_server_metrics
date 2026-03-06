# Server Metrics 2026-03-06 16:52:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 23423.1 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 700357
telemt_connections_bad_total 11246
telemt_handshake_timeouts_total 3148
telemt_upstream_connect_attempt_total 11493
telemt_upstream_connect_success_total 11424
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 11452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 2116
telemt_me_reconnect_success_total 2100
telemt_me_reader_eof_total 2202
telemt_me_idle_close_by_peer_total 2202
telemt_me_route_drop_no_conn_total 300526
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3541
telemt_desync_full_logged_total 855
telemt_desync_suppressed_total 2686
telemt_desync_frames_bucket_total{bucket="1_2"} 848
telemt_desync_frames_bucket_total{bucket="3_10"} 1230
telemt_desync_frames_bucket_total{bucket="gt_10"} 1463
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2205
telemt_me_writer_restored_same_endpoint_total 2094
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 601848
telemt_user_connections_current{user="hello"} 1011
telemt_user_octets_from_client{user="hello"} 13212623896 (12.31 GB)
telemt_user_octets_to_client{user="hello"} 221168238532 (205.98 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 23422.9 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263293
telemt_connections_bad_total 955
telemt_handshake_timeouts_total 7708
telemt_upstream_connect_attempt_total 10728
telemt_upstream_connect_success_total 10703
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 10728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 960
telemt_me_reconnect_success_total 939
telemt_me_reader_eof_total 991
telemt_me_idle_close_by_peer_total 991
telemt_me_route_drop_no_conn_total 147207
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 854
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 393
telemt_pool_swap_total 6
telemt_pool_force_close_total 239
telemt_me_writer_removed_unexpected_total 992
telemt_me_writer_restored_same_endpoint_total 939
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 242157
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 2824864128 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 98868878228 (92.08 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 23422.8 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518821
telemt_connections_bad_total 5481
telemt_handshake_timeouts_total 51823
telemt_upstream_connect_attempt_total 19967
telemt_upstream_connect_success_total 19872
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 19942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 292
telemt_me_reconnect_attempts_total 6787
telemt_me_reconnect_success_total 6760
telemt_me_reader_eof_total 7171
telemt_me_idle_close_by_peer_total 7171
telemt_me_route_drop_no_conn_total 268370
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1164
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 817
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 442
telemt_desync_frames_bucket_total{bucket="gt_10"} 452
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 7184
telemt_me_writer_restored_same_endpoint_total 6753
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 445111
telemt_user_connections_current{user="hello"} 595
telemt_user_octets_from_client{user="hello"} 6431450528 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 137625249560 (128.17 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 22738.7 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491664
telemt_connections_bad_total 167889
telemt_handshake_timeouts_total 12402
telemt_upstream_connect_attempt_total 13883
telemt_upstream_connect_success_total 13881
telemt_upstream_connect_attempts_per_request{bucket="1"} 13881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5873
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 3332
telemt_me_reconnect_success_total 3312
telemt_me_reader_eof_total 3442
telemt_me_idle_close_by_peer_total 3442
telemt_me_route_drop_no_conn_total 154912
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 354
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 3448
telemt_me_writer_restored_same_endpoint_total 3311
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 274764
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 4673074784 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 95960496356 (89.37 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 23423.2 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419607
telemt_connections_bad_total 11055
telemt_handshake_timeouts_total 3785
telemt_upstream_connect_attempt_total 10246
telemt_upstream_connect_success_total 10229
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 1773
telemt_me_reconnect_success_total 1755
telemt_me_reader_eof_total 1850
telemt_me_idle_close_by_peer_total 1849
telemt_me_route_drop_no_conn_total 204393
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 812
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 525
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1854
telemt_me_writer_restored_same_endpoint_total 1752
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 385332
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 15641297972 (14.57 GB)
telemt_user_octets_to_client{user="hello"} 196763031516 (183.25 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 84
```