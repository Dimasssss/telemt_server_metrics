# Server Metrics 2026-03-14 06:14:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 173747.9 (48h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4893790
telemt_connections_bad_total 40033
telemt_handshake_timeouts_total 112609
telemt_upstream_connect_attempt_total 36488
telemt_upstream_connect_success_total 36251
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 36488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 7311
telemt_me_reconnect_attempts_total 35430
telemt_me_reconnect_success_total 25282
telemt_me_reader_eof_total 27132
telemt_me_idle_close_by_peer_total 27131
telemt_me_route_drop_no_conn_total 1854674
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4491482
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17255
telemt_desync_full_logged_total 4660
telemt_desync_suppressed_total 12595
telemt_desync_frames_bucket_total{bucket="1_2"} 4306
telemt_desync_frames_bucket_total{bucket="3_10"} 6591
telemt_desync_frames_bucket_total{bucket="gt_10"} 6358
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 25961
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25269
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 679
telemt_user_connections_total{user="hello"} 4493003
telemt_user_connections_current{user="hello"} 1276
telemt_user_octets_from_client{user="hello"} 65620278600 (61.11 GB)
telemt_user_octets_to_client{user="hello"} 1416938549089 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 73411.8 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 799733
telemt_connections_bad_total 53662
telemt_handshake_timeouts_total 14649
telemt_upstream_connect_attempt_total 19977
telemt_upstream_connect_success_total 19707
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 19977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8598
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 2138
telemt_me_reconnect_attempts_total 17483
telemt_me_reconnect_success_total 14022
telemt_me_reader_eof_total 14905
telemt_me_idle_close_by_peer_total 14904
telemt_me_route_drop_no_conn_total 261435
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 633145
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1867
telemt_desync_full_logged_total 562
telemt_desync_suppressed_total 1305
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 839
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14325
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14014
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 635096
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 6687896665 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 212994158384 (198.37 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 203368.6 (56h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3515650
telemt_connections_bad_total 38551
telemt_handshake_timeouts_total 231632
telemt_upstream_connect_attempt_total 45988
telemt_upstream_connect_success_total 45967
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10651
telemt_me_reconnect_attempts_total 40531
telemt_me_reconnect_success_total 35558
telemt_me_reader_eof_total 37764
telemt_me_idle_close_by_peer_total 37763
telemt_me_route_drop_no_conn_total 1202993
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2931891
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9676
telemt_desync_full_logged_total 3249
telemt_desync_suppressed_total 6427
telemt_desync_frames_bucket_total{bucket="1_2"} 1692
telemt_desync_frames_bucket_total{bucket="3_10"} 3492
telemt_desync_frames_bucket_total{bucket="gt_10"} 4492
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 36052
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35517
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 494
telemt_user_connections_total{user="hello"} 2931053
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 48237744160 (44.92 GB)
telemt_user_octets_to_client{user="hello"} 1049015535857 (976.97 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 203371.2 (56h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2351343
telemt_connections_bad_total 23182
telemt_handshake_timeouts_total 274478
telemt_upstream_connect_attempt_total 63430
telemt_upstream_connect_success_total 60945
telemt_upstream_connect_fail_total 2348
telemt_upstream_connect_attempts_per_request{bucket="1"} 63156
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2347
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20500
telemt_me_reconnect_attempts_total 52869
telemt_me_reconnect_success_total 43826
telemt_me_reader_eof_total 46984
telemt_me_idle_close_by_peer_total 46977
telemt_me_route_drop_no_conn_total 794165
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1857793
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3893
telemt_desync_full_logged_total 1258
telemt_desync_suppressed_total 2635
telemt_desync_frames_bucket_total{bucket="1_2"} 1050
telemt_desync_frames_bucket_total{bucket="3_10"} 1617
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 180
telemt_me_writer_removed_unexpected_total 44486
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43802
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 1863821
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 28166730067 (26.23 GB)
telemt_user_octets_to_client{user="hello"} 684758614618 (637.73 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 72804.4 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 774010
telemt_connections_bad_total 8069
telemt_handshake_timeouts_total 9087
telemt_upstream_connect_attempt_total 18648
telemt_upstream_connect_success_total 18150
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 18648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_timeout_total 1570
telemt_me_reconnect_attempts_total 58461
telemt_me_reconnect_success_total 14532
telemt_me_reader_eof_total 16260
telemt_me_idle_close_by_peer_total 16259
telemt_me_route_drop_no_conn_total 297868
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 723000
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1764
telemt_desync_full_logged_total 565
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 554
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 16030
telemt_me_refill_failed_total 1368
telemt_me_writer_restored_same_endpoint_total 14527
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1498
telemt_user_connections_total{user="hello"} 722854
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 12865549496 (11.98 GB)
telemt_user_octets_to_client{user="hello"} 242373121156 (225.73 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 54
```