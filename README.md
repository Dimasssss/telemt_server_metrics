# Server Metrics 2026-03-15 17:19:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 68673.6 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2389254
telemt_connections_bad_total 148047
telemt_handshake_timeouts_total 30170
telemt_upstream_connect_attempt_total 13432
telemt_upstream_connect_success_total 13374
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 13432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 14819
telemt_me_reconnect_success_total 9922
telemt_me_reader_eof_total 10607
telemt_me_idle_close_by_peer_total 10607
telemt_me_route_drop_no_conn_total 822314
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1994969
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7838
telemt_desync_full_logged_total 2124
telemt_desync_suppressed_total 5714
telemt_desync_frames_bucket_total{bucket="1_2"} 1907
telemt_desync_frames_bucket_total{bucket="3_10"} 3008
telemt_desync_frames_bucket_total{bucket="gt_10"} 2923
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10241
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9911
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 1994453
telemt_user_connections_current{user="hello"} 2622
telemt_user_octets_from_client{user="hello"} 29431215432 (27.41 GB)
telemt_user_octets_to_client{user="hello"} 756756951292 (704.78 GB)
telemt_user_unique_ips_current{user="hello"} 714
telemt_user_unique_ips_recent_window{user="hello"} 308
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 68674.5 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 921342
telemt_connections_bad_total 49178
telemt_handshake_timeouts_total 61904
telemt_upstream_connect_attempt_total 17271
telemt_upstream_connect_success_total 17179
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 17271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7865
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14576
telemt_me_reconnect_success_total 13370
telemt_me_reader_eof_total 14146
telemt_me_idle_close_by_peer_total 14146
telemt_me_route_drop_no_conn_total 238386
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711927
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2176
telemt_desync_full_logged_total 731
telemt_desync_suppressed_total 1445
telemt_desync_frames_bucket_total{bucket="1_2"} 774
telemt_desync_frames_bucket_total{bucket="3_10"} 817
telemt_desync_frames_bucket_total{bucket="gt_10"} 585
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13583
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13358
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 712165
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 10301289795 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 270203777904 (251.65 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 68674.4 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2071706
telemt_connections_bad_total 49528
telemt_handshake_timeouts_total 211356
telemt_upstream_connect_attempt_total 14934
telemt_upstream_connect_success_total 14864
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12649
telemt_me_reconnect_success_total 11380
telemt_me_reader_eof_total 12057
telemt_me_idle_close_by_peer_total 12057
telemt_me_route_drop_no_conn_total 536430
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1270526
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3262
telemt_desync_full_logged_total 1173
telemt_desync_suppressed_total 2089
telemt_desync_frames_bucket_total{bucket="1_2"} 747
telemt_desync_frames_bucket_total{bucket="3_10"} 1264
telemt_desync_frames_bucket_total{bucket="gt_10"} 1251
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11580
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11361
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 1266457
telemt_user_connections_current{user="hello"} 1443
telemt_user_octets_from_client{user="hello"} 19618058784 (18.27 GB)
telemt_user_octets_to_client{user="hello"} 451530119492 (420.52 GB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 68674.3 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 992863
telemt_connections_bad_total 81699
telemt_handshake_timeouts_total 48018
telemt_upstream_connect_attempt_total 170365
telemt_upstream_connect_success_total 169796
telemt_upstream_connect_fail_total 569
telemt_upstream_connect_attempts_per_request{bucket="1"} 170365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 569
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 60044
telemt_me_reconnect_success_total 13372
telemt_me_reader_eof_total 15190
telemt_me_idle_close_by_peer_total 15190
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 230704
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 613058
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1748
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 1285
telemt_desync_frames_bucket_total{bucket="1_2"} 450
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 623
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14972
telemt_me_refill_failed_total 1460
telemt_me_writer_restored_same_endpoint_total 13336
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1600
telemt_user_connections_total{user="hello"} 765580
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 14271145513 (13.29 GB)
telemt_user_octets_to_client{user="hello"} 274287066708 (255.45 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 68675.2 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1001136
telemt_connections_bad_total 12073
telemt_handshake_timeouts_total 22490
telemt_upstream_connect_attempt_total 15227
telemt_upstream_connect_success_total 15144
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15377
telemt_me_reconnect_success_total 11682
telemt_me_reader_eof_total 12463
telemt_me_idle_close_by_peer_total 12463
telemt_me_route_drop_no_conn_total 249727
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 828047
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2783
telemt_desync_full_logged_total 940
telemt_desync_suppressed_total 1843
telemt_desync_frames_bucket_total{bucket="1_2"} 864
telemt_desync_frames_bucket_total{bucket="3_10"} 1036
telemt_desync_frames_bucket_total{bucket="gt_10"} 883
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 11939
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11674
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 828078
telemt_user_connections_current{user="hello"} 959
telemt_user_octets_from_client{user="hello"} 10343805536 (9.63 GB)
telemt_user_octets_to_client{user="hello"} 292874845628 (272.76 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 120
```