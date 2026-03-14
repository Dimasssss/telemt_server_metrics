# Server Metrics 2026-03-14 18:46:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 19757.1 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 798189
telemt_connections_bad_total 40346
telemt_handshake_timeouts_total 11271
telemt_upstream_connect_attempt_total 3758
telemt_upstream_connect_success_total 3743
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3518
telemt_me_reconnect_success_total 2716
telemt_me_reader_eof_total 2851
telemt_me_idle_close_by_peer_total 2851
telemt_me_route_drop_no_conn_total 305879
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 706977
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2435
telemt_desync_full_logged_total 699
telemt_desync_suppressed_total 1736
telemt_desync_frames_bucket_total{bucket="1_2"} 585
telemt_desync_frames_bucket_total{bucket="3_10"} 906
telemt_desync_frames_bucket_total{bucket="gt_10"} 944
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2784
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2707
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 706906
telemt_user_connections_current{user="hello"} 1811
telemt_user_octets_from_client{user="hello"} 12275692556 (11.43 GB)
telemt_user_octets_to_client{user="hello"} 234601096488 (218.49 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 19762.4 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309015
telemt_connections_bad_total 22906
telemt_handshake_timeouts_total 9065
telemt_upstream_connect_attempt_total 4119
telemt_upstream_connect_success_total 4069
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 4119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 382
telemt_me_reconnect_attempts_total 3836
telemt_me_reconnect_success_total 3043
telemt_me_reader_eof_total 3176
telemt_me_idle_close_by_peer_total 3176
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 96520
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258379
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1058
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 732
telemt_desync_frames_bucket_total{bucket="1_2"} 411
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3133
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3027
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 258302
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 3606032596 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 93106471700 (86.71 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 19625.3 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 649698
telemt_connections_bad_total 2454
telemt_handshake_timeouts_total 131123
telemt_upstream_connect_attempt_total 3856
telemt_upstream_connect_success_total 3843
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 6739
telemt_me_reconnect_success_total 2832
telemt_me_reader_eof_total 3042
telemt_me_idle_close_by_peer_total 3042
telemt_me_route_drop_no_conn_total 157902
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441154
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1500
telemt_desync_full_logged_total 582
telemt_desync_suppressed_total 918
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 778
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2979
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2799
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 441059
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 6496018900 (6.05 GB)
telemt_user_octets_to_client{user="hello"} 157661049576 (146.83 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 19479.9 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357440
telemt_connections_bad_total 83729
telemt_handshake_timeouts_total 43638
telemt_upstream_connect_attempt_total 4689
telemt_upstream_connect_success_total 4688
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 4599
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 3845
telemt_me_idle_close_by_peer_total 3845
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 79409
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224353
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 497
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 329
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3751
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3674
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 224291
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 3323384552 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 70029132964 (65.22 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 19775.2 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303137
telemt_connections_bad_total 1217
telemt_handshake_timeouts_total 3454
telemt_upstream_connect_attempt_total 4044
telemt_upstream_connect_success_total 3964
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 4044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 3629
telemt_me_reconnect_success_total 2960
telemt_me_reader_eof_total 3122
telemt_me_idle_close_by_peer_total 3122
telemt_me_route_drop_no_conn_total 94824
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280629
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 689
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 420
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3042
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2942
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 280616
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 4326755892 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 121106649328 (112.79 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 102
```