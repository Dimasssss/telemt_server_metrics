# Server Metrics 2026-03-11 20:38:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 108692.4 (30h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2756724
telemt_connections_bad_total 57676
telemt_handshake_timeouts_total 62203
telemt_upstream_connect_attempt_total 23002
telemt_upstream_connect_success_total 22990
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5413
telemt_me_reconnect_attempts_total 35385
telemt_me_reconnect_success_total 17491
telemt_me_reader_eof_total 18883
telemt_me_idle_close_by_peer_total 18883
telemt_me_route_drop_no_conn_total 1037239
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2507081
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12659
telemt_desync_full_logged_total 3514
telemt_desync_suppressed_total 9145
telemt_desync_frames_bucket_total{bucket="1_2"} 3121
telemt_desync_frames_bucket_total{bucket="3_10"} 4865
telemt_desync_frames_bucket_total{bucket="gt_10"} 4673
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18253
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17485
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 762
telemt_user_connections_total{user="hello"} 2505423
telemt_user_connections_current{user="hello"} 1019
telemt_user_octets_from_client{user="hello"} 38044257892 (35.43 GB)
telemt_user_octets_to_client{user="hello"} 720752000156 (671.25 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 108748.8 (30h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1011932
telemt_connections_bad_total 17046
telemt_handshake_timeouts_total 90411
telemt_upstream_connect_attempt_total 33218
telemt_upstream_connect_success_total 30245
telemt_upstream_connect_fail_total 2973
telemt_upstream_connect_attempts_per_request{bucket="1"} 33218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2089
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2973
telemt_me_keepalive_timeout_total 2887
telemt_me_reconnect_attempts_total 23960
telemt_me_reconnect_success_total 21835
telemt_me_reader_eof_total 23133
telemt_me_idle_close_by_peer_total 23130
telemt_me_route_drop_no_conn_total 383015
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 845093
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3353
telemt_desync_full_logged_total 1090
telemt_desync_suppressed_total 2263
telemt_desync_frames_bucket_total{bucket="1_2"} 1088
telemt_desync_frames_bucket_total{bucket="3_10"} 1182
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 22157
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21812
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 847532
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 10267847050 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 249369819064 (232.24 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 108748.7 (30h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1759655
telemt_connections_bad_total 11155
telemt_handshake_timeouts_total 135428
telemt_upstream_connect_attempt_total 27502
telemt_upstream_connect_success_total 27152
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 27502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_keepalive_timeout_total 2030
telemt_me_reconnect_attempts_total 58333
telemt_me_reconnect_success_total 20580
telemt_me_reader_eof_total 22619
telemt_me_idle_close_by_peer_total 22619
telemt_me_route_drop_no_conn_total 640090
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1547551
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4169
telemt_desync_full_logged_total 1228
telemt_desync_suppressed_total 2941
telemt_desync_frames_bucket_total{bucket="1_2"} 970
telemt_desync_frames_bucket_total{bucket="3_10"} 1584
telemt_desync_frames_bucket_total{bucket="gt_10"} 1615
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22042
telemt_me_refill_failed_total 1174
telemt_me_writer_restored_same_endpoint_total 20568
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1462
telemt_user_connections_total{user="hello"} 1547181
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 19857939313 (18.49 GB)
telemt_user_octets_to_client{user="hello"} 474110778033 (441.55 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 108749.1 (30h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1257933
telemt_connections_bad_total 78247
telemt_handshake_timeouts_total 111455
telemt_upstream_connect_attempt_total 29241
telemt_upstream_connect_success_total 29241
telemt_upstream_connect_attempts_per_request{bucket="1"} 29241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1530
telemt_me_reconnect_attempts_total 28427
telemt_me_reconnect_success_total 23805
telemt_me_reader_eof_total 25276
telemt_me_idle_close_by_peer_total 25275
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 422749
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1032484
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2196
telemt_desync_full_logged_total 826
telemt_desync_suppressed_total 1370
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 680
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 24205
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23772
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 1031612
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 12214277704 (11.38 GB)
telemt_user_octets_to_client{user="hello"} 313359361548 (291.84 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13425.1 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196253
telemt_connections_bad_total 5148
telemt_handshake_timeouts_total 2259
telemt_upstream_connect_attempt_total 3855
telemt_upstream_connect_success_total 3854
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 3163
telemt_me_reconnect_success_total 3134
telemt_me_reader_eof_total 3231
telemt_me_idle_close_by_peer_total 3231
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 66046
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172920
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 437
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3171
telemt_me_writer_restored_same_endpoint_total 3109
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 172883
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 9553345200 (8.90 GB)
telemt_user_octets_to_client{user="hello"} 59909387852 (55.79 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 62
```