# Server Metrics 2026-03-13 12:47:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 110941.0 (30h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3314766
telemt_connections_bad_total 37358
telemt_handshake_timeouts_total 57553
telemt_upstream_connect_attempt_total 21884
telemt_upstream_connect_success_total 21763
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 21884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10488
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 2104
telemt_me_reconnect_attempts_total 26307
telemt_me_reconnect_success_total 16223
telemt_me_reader_eof_total 17444
telemt_me_idle_close_by_peer_total 17443
telemt_me_route_drop_no_conn_total 1228357
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3038775
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12781
telemt_desync_full_logged_total 3322
telemt_desync_suppressed_total 9459
telemt_desync_frames_bucket_total{bucket="1_2"} 3254
telemt_desync_frames_bucket_total{bucket="3_10"} 4821
telemt_desync_frames_bucket_total{bucket="gt_10"} 4706
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 16765
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16210
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 3038680
telemt_user_connections_current{user="hello"} 1811
telemt_user_octets_from_client{user="hello"} 42211149908 (39.31 GB)
telemt_user_octets_to_client{user="hello"} 980518264808 (913.18 GB)
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 10604.5 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144497
telemt_connections_bad_total 8619
telemt_handshake_timeouts_total 3441
telemt_upstream_connect_attempt_total 2609
telemt_upstream_connect_success_total 2535
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 2609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 3189
telemt_me_reconnect_success_total 1962
telemt_me_reader_eof_total 2060
telemt_me_idle_close_by_peer_total 2060
telemt_me_route_drop_no_conn_total 51395
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128879
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 352
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2015
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1955
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 128904
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 1257728008 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 35011451964 (32.61 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 140561.4 (39h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2509338
telemt_connections_bad_total 26333
telemt_handshake_timeouts_total 165145
telemt_upstream_connect_attempt_total 31994
telemt_upstream_connect_success_total 31984
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 31994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15169
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3179
telemt_me_reconnect_attempts_total 27169
telemt_me_reconnect_success_total 24623
telemt_me_reader_eof_total 26106
telemt_me_idle_close_by_peer_total 26105
telemt_me_route_drop_no_conn_total 839233
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2039446
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6882
telemt_desync_full_logged_total 2221
telemt_desync_suppressed_total 4661
telemt_desync_frames_bucket_total{bucket="1_2"} 1083
telemt_desync_frames_bucket_total{bucket="3_10"} 2521
telemt_desync_frames_bucket_total{bucket="gt_10"} 3278
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 24907
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24582
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 2038859
telemt_user_connections_current{user="hello"} 1078
telemt_user_octets_from_client{user="hello"} 34419615820 (32.06 GB)
telemt_user_octets_to_client{user="hello"} 735350704725 (684.85 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 140561.7 (39h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1601044
telemt_connections_bad_total 17872
telemt_handshake_timeouts_total 113128
telemt_upstream_connect_attempt_total 45323
telemt_upstream_connect_success_total 43003
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 45049
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11827
telemt_me_reconnect_attempts_total 39095
telemt_me_reconnect_success_total 30131
telemt_me_reader_eof_total 32401
telemt_me_idle_close_by_peer_total 32394
telemt_me_route_drop_no_conn_total 568984
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1334885
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2609
telemt_desync_full_logged_total 856
telemt_desync_suppressed_total 1753
telemt_desync_frames_bucket_total{bucket="1_2"} 703
telemt_desync_frames_bucket_total{bucket="3_10"} 1045
telemt_desync_frames_bucket_total{bucket="gt_10"} 861
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 30633
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30107
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 502
telemt_user_connections_total{user="hello"} 1339607
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 19927527241 (18.56 GB)
telemt_user_octets_to_client{user="hello"} 523081711314 (487.16 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9997.4 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149184
telemt_connections_bad_total 2419
telemt_handshake_timeouts_total 1302
telemt_upstream_connect_attempt_total 2051
telemt_upstream_connect_success_total 1977
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 2051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 9488
telemt_me_reconnect_success_total 1416
telemt_me_reader_eof_total 1646
telemt_me_idle_close_by_peer_total 1646
telemt_me_route_drop_no_conn_total 57993
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140188
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 523
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 352
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1662
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1412
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 140172
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 1574450096 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 45593327320 (42.46 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 117
```