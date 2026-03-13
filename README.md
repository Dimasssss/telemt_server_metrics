# Server Metrics 2026-03-13 15:05:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 119195.6 (33h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3691616
telemt_connections_bad_total 37420
telemt_handshake_timeouts_total 74333
telemt_upstream_connect_attempt_total 23252
telemt_upstream_connect_success_total 23120
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 23252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 2184
telemt_me_reconnect_attempts_total 27277
telemt_me_reconnect_success_total 17190
telemt_me_reader_eof_total 18476
telemt_me_idle_close_by_peer_total 18475
telemt_me_route_drop_no_conn_total 1369828
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3381888
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13839
telemt_desync_full_logged_total 3648
telemt_desync_suppressed_total 10191
telemt_desync_frames_bucket_total{bucket="1_2"} 3488
telemt_desync_frames_bucket_total{bucket="3_10"} 5249
telemt_desync_frames_bucket_total{bucket="gt_10"} 5102
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 17742
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17177
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 3381644
telemt_user_connections_current{user="hello"} 1992
telemt_user_octets_from_client{user="hello"} 46290270692 (43.11 GB)
telemt_user_octets_to_client{user="hello"} 1066935589836 (993.66 GB)
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 287
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 18859.6 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270055
telemt_connections_bad_total 14518
telemt_handshake_timeouts_total 6890
telemt_upstream_connect_attempt_total 4513
telemt_upstream_connect_success_total 4429
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 4513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2119
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 5748
telemt_me_reconnect_success_total 3458
telemt_me_reader_eof_total 3668
telemt_me_idle_close_by_peer_total 3668
telemt_me_route_drop_no_conn_total 97864
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241589
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 933
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 700
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 461
telemt_desync_frames_bucket_total{bucket="gt_10"} 301
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3569
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3451
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 241616
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 2469951392 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 68296861488 (63.61 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 148816.3 (41h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2738389
telemt_connections_bad_total 27406
telemt_handshake_timeouts_total 182220
telemt_upstream_connect_attempt_total 33494
telemt_upstream_connect_success_total 33484
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3264
telemt_me_reconnect_attempts_total 28282
telemt_me_reconnect_success_total 25733
telemt_me_reader_eof_total 27290
telemt_me_idle_close_by_peer_total 27289
telemt_me_route_drop_no_conn_total 923778
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2244537
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8010
telemt_desync_full_logged_total 2633
telemt_desync_suppressed_total 5377
telemt_desync_frames_bucket_total{bucket="1_2"} 1266
telemt_desync_frames_bucket_total{bucket="3_10"} 2924
telemt_desync_frames_bucket_total{bucket="gt_10"} 3820
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 26032
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25692
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 2243910
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 36963416660 (34.42 GB)
telemt_user_octets_to_client{user="hello"} 790552092129 (736.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 148816.6 (41h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1744628
telemt_connections_bad_total 18126
telemt_handshake_timeouts_total 131018
telemt_upstream_connect_attempt_total 46974
telemt_upstream_connect_success_total 44645
telemt_upstream_connect_fail_total 2192
telemt_upstream_connect_attempts_per_request{bucket="1"} 46700
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17699
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2191
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11852
telemt_me_reconnect_attempts_total 40347
telemt_me_reconnect_success_total 31376
telemt_me_reader_eof_total 33721
telemt_me_idle_close_by_peer_total 33714
telemt_me_route_drop_no_conn_total 624535
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1457290
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2933
telemt_desync_full_logged_total 948
telemt_desync_suppressed_total 1985
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 1220
telemt_desync_frames_bucket_total{bucket="gt_10"} 932
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 31894
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31352
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 1462002
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 22849792577 (21.28 GB)
telemt_user_octets_to_client{user="hello"} 559706306074 (521.27 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 18252.2 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291927
telemt_connections_bad_total 3955
telemt_handshake_timeouts_total 2724
telemt_upstream_connect_attempt_total 3949
telemt_upstream_connect_success_total 3822
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 3949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 13436
telemt_me_reconnect_success_total 2862
telemt_me_reader_eof_total 3226
telemt_me_idle_close_by_peer_total 3226
telemt_me_route_drop_no_conn_total 115438
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273001
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 845
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 575
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3203
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 2858
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 341
telemt_user_connections_total{user="hello"} 272980
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 3149229840 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 88107570612 (82.06 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 124
```