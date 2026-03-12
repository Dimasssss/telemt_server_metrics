# Server Metrics 2026-03-12 02:15:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 16215.1 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133861
telemt_connections_bad_total 1351
telemt_handshake_timeouts_total 2445
telemt_upstream_connect_attempt_total 3721
telemt_upstream_connect_success_total 3721
telemt_upstream_connect_attempts_per_request{bucket="1"} 3721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 2918
telemt_me_reconnect_success_total 2906
telemt_me_reader_eof_total 3065
telemt_me_idle_close_by_peer_total 3065
telemt_me_route_drop_no_conn_total 47931
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125958
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
telemt_me_writer_removed_unexpected_total 2941
telemt_me_writer_restored_same_endpoint_total 2890
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 125817
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 885844796 (844.81 MB)
telemt_user_octets_to_client{user="hello"} 37440588196 (34.87 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 16215.8 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45617
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 619
telemt_upstream_connect_attempt_total 4684
telemt_upstream_connect_success_total 4681
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 3697
telemt_me_reconnect_success_total 3671
telemt_me_reader_eof_total 3886
telemt_me_idle_close_by_peer_total 3886
telemt_me_route_drop_no_conn_total 12350
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42560
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 50
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3700
telemt_me_writer_restored_same_endpoint_total 3662
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 42739
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 702977663 (670.41 MB)
telemt_user_octets_to_client{user="hello"} 14678283354 (13.67 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 16215.4 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202576
telemt_connections_bad_total 1144
telemt_handshake_timeouts_total 14131
telemt_upstream_connect_attempt_total 5011
telemt_upstream_connect_success_total 5009
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 3882
telemt_me_reconnect_success_total 3831
telemt_me_reader_eof_total 3951
telemt_me_idle_close_by_peer_total 3951
telemt_me_route_drop_no_conn_total 24194
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77510
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
telemt_me_writer_removed_unexpected_total 3781
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3790
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 77851
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 682006292 (650.41 MB)
telemt_user_octets_to_client{user="hello"} 26053339137 (24.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 16215.9 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68526
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 1623
telemt_upstream_connect_attempt_total 4833
telemt_upstream_connect_success_total 4810
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 4005
telemt_me_reconnect_success_total 3990
telemt_me_reader_eof_total 4212
telemt_me_idle_close_by_peer_total 4212
telemt_me_route_drop_no_conn_total 24300
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65874
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 105
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4014
telemt_me_writer_restored_same_endpoint_total 3969
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 65865
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 391623216 (373.48 MB)
telemt_user_octets_to_client{user="hello"} 15026024980 (13.99 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16215.8 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88574
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 616
telemt_upstream_connect_attempt_total 6100
telemt_upstream_connect_success_total 6041
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 6100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 6706
telemt_me_reconnect_success_total 5211
telemt_me_reader_eof_total 5403
telemt_me_idle_close_by_peer_total 5403
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 21934
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84164
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 293
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5294
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5197
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 84143
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 470438612 (448.65 MB)
telemt_user_octets_to_client{user="hello"} 17813364508 (16.59 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 35
```