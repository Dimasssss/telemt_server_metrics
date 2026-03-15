# Server Metrics 2026-03-15 18:15:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 72047.0 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2573495
telemt_connections_bad_total 151187
telemt_handshake_timeouts_total 33659
telemt_upstream_connect_attempt_total 13912
telemt_upstream_connect_success_total 13853
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 13912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 15154
telemt_me_reconnect_success_total 10255
telemt_me_reader_eof_total 10959
telemt_me_idle_close_by_peer_total 10959
telemt_me_route_drop_no_conn_total 892230
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2149063
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8321
telemt_desync_full_logged_total 2277
telemt_desync_suppressed_total 6044
telemt_desync_frames_bucket_total{bucket="1_2"} 2055
telemt_desync_frames_bucket_total{bucket="3_10"} 3170
telemt_desync_frames_bucket_total{bucket="gt_10"} 3096
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10580
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10244
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 2148533
telemt_user_connections_current{user="hello"} 2497
telemt_user_octets_from_client{user="hello"} 32380317776 (30.16 GB)
telemt_user_octets_to_client{user="hello"} 819807820932 (763.51 GB)
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 310
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 72047.7 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 995746
telemt_connections_bad_total 56812
telemt_handshake_timeouts_total 63619
telemt_upstream_connect_attempt_total 17852
telemt_upstream_connect_success_total 17756
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 15006
telemt_me_reconnect_success_total 13794
telemt_me_reader_eof_total 14596
telemt_me_idle_close_by_peer_total 14596
telemt_me_route_drop_no_conn_total 258651
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 769701
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2229
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1471
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 840
telemt_desync_frames_bucket_total{bucket="gt_10"} 609
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 14012
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13782
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 769929
telemt_user_connections_current{user="hello"} 857
telemt_user_octets_from_client{user="hello"} 11171905939 (10.40 GB)
telemt_user_octets_to_client{user="hello"} 289104415420 (269.25 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 72047.8 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2186095
telemt_connections_bad_total 51188
telemt_handshake_timeouts_total 215382
telemt_upstream_connect_attempt_total 15468
telemt_upstream_connect_success_total 15391
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 15468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 13031
telemt_me_reconnect_success_total 11761
telemt_me_reader_eof_total 12459
telemt_me_idle_close_by_peer_total 12459
telemt_me_route_drop_no_conn_total 569511
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1369102
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3566
telemt_desync_full_logged_total 1283
telemt_desync_suppressed_total 2283
telemt_desync_frames_bucket_total{bucket="1_2"} 818
telemt_desync_frames_bucket_total{bucket="3_10"} 1385
telemt_desync_frames_bucket_total{bucket="gt_10"} 1363
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11967
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11742
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 1364977
telemt_user_connections_current{user="hello"} 1438
telemt_user_octets_from_client{user="hello"} 25390418072 (23.65 GB)
telemt_user_octets_to_client{user="hello"} 510948975584 (475.86 GB)
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 72047.5 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1060383
telemt_connections_bad_total 82089
telemt_handshake_timeouts_total 52032
telemt_upstream_connect_attempt_total 170887
telemt_upstream_connect_success_total 170283
telemt_upstream_connect_fail_total 604
telemt_upstream_connect_attempts_per_request{bucket="1"} 170887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 604
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61788
telemt_me_reconnect_success_total 13722
telemt_me_reader_eof_total 15588
telemt_me_idle_close_by_peer_total 15588
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 252504
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 673898
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1881
telemt_desync_full_logged_total 519
telemt_desync_suppressed_total 1362
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 728
telemt_desync_frames_bucket_total{bucket="gt_10"} 674
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 15368
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13686
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1646
telemt_user_connections_total{user="hello"} 826411
telemt_user_connections_current{user="hello"} 891
telemt_user_octets_from_client{user="hello"} 15288708065 (14.24 GB)
telemt_user_octets_to_client{user="hello"} 295034787576 (274.77 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 72048.6 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1075900
telemt_connections_bad_total 12621
telemt_handshake_timeouts_total 23413
telemt_upstream_connect_attempt_total 15784
telemt_upstream_connect_success_total 15699
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 15784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15787
telemt_me_reconnect_success_total 12092
telemt_me_reader_eof_total 12896
telemt_me_idle_close_by_peer_total 12896
telemt_me_route_drop_no_conn_total 272423
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 892548
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3116
telemt_desync_full_logged_total 1028
telemt_desync_suppressed_total 2088
telemt_desync_frames_bucket_total{bucket="1_2"} 942
telemt_desync_frames_bucket_total{bucket="3_10"} 1152
telemt_desync_frames_bucket_total{bucket="gt_10"} 1022
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12353
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 12084
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 892571
telemt_user_connections_current{user="hello"} 902
telemt_user_octets_from_client{user="hello"} 11022523432 (10.27 GB)
telemt_user_octets_to_client{user="hello"} 311748660732 (290.34 GB)
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 118
```