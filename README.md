# Server Metrics 2026-03-04 09:44:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 45251.0 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 623744
telemt_connections_bad_total 10944
telemt_handshake_timeouts_total 7203
telemt_upstream_connect_attempt_total 29830
telemt_upstream_connect_success_total 29702
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 29702
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 6619
telemt_me_reconnect_success_total 6576
telemt_me_reader_eof_total 6776
telemt_me_idle_close_by_peer_total 6776
telemt_me_route_drop_no_conn_total 221409
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 183
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1088
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 707
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 411
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 6776
telemt_me_writer_restored_same_endpoint_total 6555
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 514153
telemt_user_connections_current{user="hello"} 1017
telemt_user_octets_from_client{user="hello"} 5715694924 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 150820004408 (140.46 GB)
telemt_user_unique_ips_current{user="hello"} 87
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 45247.6 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244644
telemt_connections_bad_total 2038
telemt_handshake_timeouts_total 25611
telemt_upstream_connect_attempt_total 93709
telemt_upstream_connect_success_total 92405
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 92399
telemt_upstream_connect_attempts_per_request{bucket="2"} 620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 1328
telemt_me_reconnect_attempts_total 54316
telemt_me_reconnect_success_total 54234
telemt_me_reader_eof_total 55632
telemt_me_idle_close_by_peer_total 55631
telemt_me_route_drop_no_conn_total 116830
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 193
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 521
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 3
telemt_pool_force_close_total 141
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55712
telemt_me_writer_restored_same_endpoint_total 54209
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 187477
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 2129810412 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 65001584488 (60.54 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 45246.4 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509230
telemt_connections_bad_total 138679
telemt_handshake_timeouts_total 15457
telemt_upstream_connect_attempt_total 65018
telemt_upstream_connect_success_total 64611
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 64610
telemt_upstream_connect_attempts_per_request{bucket="2"} 195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 864
telemt_me_reconnect_attempts_total 29322
telemt_me_reconnect_success_total 29243
telemt_me_reader_eof_total 30845
telemt_me_idle_close_by_peer_total 30842
telemt_me_route_drop_no_conn_total 171958
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 810
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 515
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 30856
telemt_me_writer_restored_same_endpoint_total 29222
telemt_me_writer_removed_unexpected_minus_restored_total 1634
telemt_user_connections_total{user="hello"} 339110
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 3609039076 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 120952032648 (112.65 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 45245.4 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327554
telemt_connections_bad_total 22816
telemt_handshake_timeouts_total 52551
telemt_upstream_connect_attempt_total 32764
telemt_upstream_connect_success_total 32629
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 32629
telemt_upstream_connect_attempts_per_request{bucket="2"} 66
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 374
telemt_me_reconnect_attempts_total 6588
telemt_me_reconnect_success_total 6567
telemt_me_reader_eof_total 6692
telemt_me_idle_close_by_peer_total 6692
telemt_me_route_drop_no_conn_total 92915
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 13
telemt_pool_force_close_total 315
telemt_me_writer_removed_unexpected_total 6692
telemt_me_writer_restored_same_endpoint_total 6546
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 231063
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 2576985424 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 80049789468 (74.55 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 45244.0 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458388
telemt_connections_bad_total 6488
telemt_handshake_timeouts_total 132146
telemt_upstream_connect_attempt_total 68154
telemt_upstream_connect_success_total 67729
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 67729
telemt_upstream_connect_attempts_per_request{bucket="2"} 200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26867
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 897
telemt_me_reconnect_attempts_total 33513
telemt_me_reconnect_success_total 33483
telemt_me_reader_eof_total 35162
telemt_me_idle_close_by_peer_total 35161
telemt_me_route_drop_no_conn_total 139990
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 408
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 277
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35174
telemt_me_writer_restored_same_endpoint_total 33458
telemt_me_writer_removed_unexpected_minus_restored_total 1716
telemt_user_connections_total{user="hello"} 300102
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 4259999036 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 74984907728 (69.84 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 83
```