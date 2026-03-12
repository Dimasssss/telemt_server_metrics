# Server Metrics 2026-03-12 02:10:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 15909.0 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131097
telemt_connections_bad_total 1351
telemt_handshake_timeouts_total 2290
telemt_upstream_connect_attempt_total 3690
telemt_upstream_connect_success_total 3690
telemt_upstream_connect_attempts_per_request{bucket="1"} 3690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 2887
telemt_me_reconnect_success_total 2875
telemt_me_reader_eof_total 3032
telemt_me_idle_close_by_peer_total 3032
telemt_me_route_drop_no_conn_total 47135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123376
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 206
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2908
telemt_me_writer_restored_same_endpoint_total 2859
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 123236
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 873578012 (833.11 MB)
telemt_user_octets_to_client{user="hello"} 36741782444 (34.22 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 15909.7 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44587
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 524
telemt_upstream_connect_attempt_total 4632
telemt_upstream_connect_success_total 4629
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 3645
telemt_me_reconnect_success_total 3619
telemt_me_reader_eof_total 3832
telemt_me_idle_close_by_peer_total 3832
telemt_me_route_drop_no_conn_total 12159
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41648
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3646
telemt_me_writer_restored_same_endpoint_total 3610
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 41827
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 696040835 (663.80 MB)
telemt_user_octets_to_client{user="hello"} 14376282426 (13.39 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 15909.6 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193803
telemt_connections_bad_total 1120
telemt_handshake_timeouts_total 13828
telemt_upstream_connect_attempt_total 4955
telemt_upstream_connect_success_total 4953
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 3826
telemt_me_reconnect_success_total 3774
telemt_me_reader_eof_total 3895
telemt_me_idle_close_by_peer_total 3895
telemt_me_route_drop_no_conn_total 23918
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75919
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3725
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3733
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 76260
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 669993176 (638.96 MB)
telemt_user_octets_to_client{user="hello"} 25697641757 (23.93 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 15909.8 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67311
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 1603
telemt_upstream_connect_attempt_total 4774
telemt_upstream_connect_success_total 4751
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 3946
telemt_me_reconnect_success_total 3931
telemt_me_reader_eof_total 4153
telemt_me_idle_close_by_peer_total 4153
telemt_me_route_drop_no_conn_total 23775
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64683
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3955
telemt_me_writer_restored_same_endpoint_total 3910
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 64674
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 381179320 (363.52 MB)
telemt_user_octets_to_client{user="hello"} 14653796544 (13.65 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15909.9 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86970
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 613
telemt_upstream_connect_attempt_total 6052
telemt_upstream_connect_success_total 5993
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 6052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2964
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 6658
telemt_me_reconnect_success_total 5163
telemt_me_reader_eof_total 5355
telemt_me_idle_close_by_peer_total 5355
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 21572
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82588
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 262
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5246
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5149
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 82567
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 405254276 (386.48 MB)
telemt_user_octets_to_client{user="hello"} 17618043828 (16.41 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 31
```