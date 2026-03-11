# Server Metrics 2026-03-11 20:08:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 106855.3 (29h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2714005
telemt_connections_bad_total 52070
telemt_handshake_timeouts_total 61113
telemt_upstream_connect_attempt_total 22588
telemt_upstream_connect_success_total 22576
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11072
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5401
telemt_me_reconnect_attempts_total 35062
telemt_me_reconnect_success_total 17168
telemt_me_reader_eof_total 18547
telemt_me_idle_close_by_peer_total 18547
telemt_me_route_drop_no_conn_total 1023291
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2474366
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12546
telemt_desync_full_logged_total 3481
telemt_desync_suppressed_total 9065
telemt_desync_frames_bucket_total{bucket="1_2"} 3092
telemt_desync_frames_bucket_total{bucket="3_10"} 4826
telemt_desync_frames_bucket_total{bucket="gt_10"} 4628
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 17923
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17162
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 755
telemt_user_connections_total{user="hello"} 2472717
telemt_user_connections_current{user="hello"} 1030
telemt_user_octets_from_client{user="hello"} 36779340512 (34.25 GB)
telemt_user_octets_to_client{user="hello"} 705222836056 (656.79 GB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 106911.9 (29h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1002265
telemt_connections_bad_total 16555
telemt_handshake_timeouts_total 90283
telemt_upstream_connect_attempt_total 32806
telemt_upstream_connect_success_total 29834
telemt_upstream_connect_fail_total 2972
telemt_upstream_connect_attempts_per_request{bucket="1"} 32806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2082
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2972
telemt_me_keepalive_timeout_total 2879
telemt_me_reconnect_attempts_total 23635
telemt_me_reconnect_success_total 21514
telemt_me_reader_eof_total 22785
telemt_me_idle_close_by_peer_total 22782
telemt_me_route_drop_no_conn_total 379017
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 836568
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3325
telemt_desync_full_logged_total 1079
telemt_desync_suppressed_total 2246
telemt_desync_frames_bucket_total{bucket="1_2"} 1065
telemt_desync_frames_bucket_total{bucket="3_10"} 1180
telemt_desync_frames_bucket_total{bucket="gt_10"} 1080
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 21828
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21491
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 839011
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 10107265174 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 244437694212 (227.65 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 106911.9 (29h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1736014
telemt_connections_bad_total 10839
telemt_handshake_timeouts_total 134636
telemt_upstream_connect_attempt_total 27278
telemt_upstream_connect_success_total 26935
telemt_upstream_connect_fail_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 27278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12205
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 343
telemt_me_keepalive_timeout_total 2011
telemt_me_reconnect_attempts_total 55523
telemt_me_reconnect_success_total 20459
telemt_me_reader_eof_total 22413
telemt_me_idle_close_by_peer_total 22413
telemt_me_route_drop_no_conn_total 631906
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1525543
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4138
telemt_desync_full_logged_total 1221
telemt_desync_suppressed_total 2917
telemt_desync_frames_bucket_total{bucket="1_2"} 967
telemt_desync_frames_bucket_total{bucket="3_10"} 1573
telemt_desync_frames_bucket_total{bucket="gt_10"} 1598
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21835
telemt_me_refill_failed_total 1090
telemt_me_writer_restored_same_endpoint_total 20447
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1376
telemt_user_connections_total{user="hello"} 1525178
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 19661599253 (18.31 GB)
telemt_user_octets_to_client{user="hello"} 467568707437 (435.46 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 106912.3 (29h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1239417
telemt_connections_bad_total 78220
telemt_handshake_timeouts_total 111116
telemt_upstream_connect_attempt_total 28792
telemt_upstream_connect_success_total 28792
telemt_upstream_connect_attempts_per_request{bucket="1"} 28792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1482
telemt_me_reconnect_attempts_total 28067
telemt_me_reconnect_success_total 23450
telemt_me_reader_eof_total 24900
telemt_me_idle_close_by_peer_total 24899
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 416349
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1014614
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2178
telemt_desync_full_logged_total 816
telemt_desync_suppressed_total 1362
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 668
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 23839
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23417
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 1013740
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 12036942584 (11.21 GB)
telemt_user_octets_to_client{user="hello"} 310397393224 (289.08 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11588.4 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178747
telemt_connections_bad_total 4827
telemt_handshake_timeouts_total 1913
telemt_upstream_connect_attempt_total 3335
telemt_upstream_connect_success_total 3334
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 2734
telemt_me_reconnect_success_total 2707
telemt_me_reader_eof_total 2783
telemt_me_idle_close_by_peer_total 2783
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 59789
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156793
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 366
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 244
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2738
telemt_me_writer_restored_same_endpoint_total 2682
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 156759
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 9440003504 (8.79 GB)
telemt_user_octets_to_client{user="hello"} 52402941232 (48.80 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 56
```