# Server Metrics 2026-03-04 08:33:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 40945.2 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480334
telemt_connections_bad_total 8025
telemt_handshake_timeouts_total 6539
telemt_upstream_connect_attempt_total 25321
telemt_upstream_connect_success_total 25208
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 25208
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 4960
telemt_me_reconnect_success_total 4924
telemt_me_reader_eof_total 5045
telemt_me_idle_close_by_peer_total 5045
telemt_me_route_drop_no_conn_total 163026
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 893
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 567
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 301
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 5045
telemt_me_writer_restored_same_endpoint_total 4903
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 407125
telemt_user_connections_current{user="hello"} 979
telemt_user_octets_from_client{user="hello"} 4786406396 (4.46 GB)
telemt_user_octets_to_client{user="hello"} 120900089204 (112.60 GB)
telemt_user_unique_ips_current{user="hello"} 102
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 40941.3 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199933
telemt_connections_bad_total 1896
telemt_handshake_timeouts_total 24153
telemt_upstream_connect_attempt_total 84138
telemt_upstream_connect_success_total 82906
telemt_upstream_connect_fail_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 82900
telemt_upstream_connect_attempts_per_request{bucket="2"} 584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 578
telemt_me_keepalive_timeout_total 1243
telemt_me_reconnect_attempts_total 48868
telemt_me_reconnect_success_total 48790
telemt_me_reader_eof_total 50017
telemt_me_idle_close_by_peer_total 50016
telemt_me_route_drop_no_conn_total 87324
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 176
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 439
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 2
telemt_pool_force_close_total 139
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 50097
telemt_me_writer_restored_same_endpoint_total 48765
telemt_me_writer_removed_unexpected_minus_restored_total 1332
telemt_user_connections_total{user="hello"} 146359
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 1748728636 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 54945770344 (51.17 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 40940.0 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411071
telemt_connections_bad_total 118664
telemt_handshake_timeouts_total 11399
telemt_upstream_connect_attempt_total 60629
telemt_upstream_connect_success_total 60255
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 60254
telemt_upstream_connect_attempts_per_request{bucket="2"} 179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 807
telemt_me_reconnect_attempts_total 27789
telemt_me_reconnect_success_total 27718
telemt_me_reader_eof_total 29264
telemt_me_idle_close_by_peer_total 29261
telemt_me_route_drop_no_conn_total 135630
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 174
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 643
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_me_writer_removed_unexpected_total 29275
telemt_me_writer_restored_same_endpoint_total 27697
telemt_me_writer_removed_unexpected_minus_restored_total 1578
telemt_user_connections_total{user="hello"} 265937
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 2578159808 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 101177718144 (94.23 GB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 40939.2 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231165
telemt_connections_bad_total 18940
telemt_handshake_timeouts_total 8501
telemt_upstream_connect_attempt_total 30759
telemt_upstream_connect_success_total 30630
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 30630
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 351
telemt_me_reconnect_attempts_total 6424
telemt_me_reconnect_success_total 6406
telemt_me_reader_eof_total 6528
telemt_me_idle_close_by_peer_total 6528
telemt_me_route_drop_no_conn_total 75299
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 171
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6528
telemt_me_writer_restored_same_endpoint_total 6385
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 184213
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 2085292820 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 64928050872 (60.47 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 40938.0 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384245
telemt_connections_bad_total 6445
telemt_handshake_timeouts_total 131963
telemt_upstream_connect_attempt_total 61319
telemt_upstream_connect_success_total 60910
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 60910
telemt_upstream_connect_attempts_per_request{bucket="2"} 192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 814
telemt_me_reconnect_attempts_total 29391
telemt_me_reconnect_success_total 29367
telemt_me_reader_eof_total 30881
telemt_me_idle_close_by_peer_total 30880
telemt_me_route_drop_no_conn_total 110460
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 175
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 260
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 30894
telemt_me_writer_restored_same_endpoint_total 29342
telemt_me_writer_removed_unexpected_minus_restored_total 1552
telemt_user_connections_total{user="hello"} 236803
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 3129931220 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 59434146212 (55.35 GB)
telemt_user_unique_ips_current{user="hello"} 36
```