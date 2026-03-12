# Server Metrics 2026-03-12 07:36:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 5882.3 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173928
telemt_connections_bad_total 1200
telemt_handshake_timeouts_total 1553
telemt_upstream_connect_attempt_total 1223
telemt_upstream_connect_success_total 1215
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 527
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 887
telemt_me_reconnect_success_total 883
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 894
telemt_me_route_drop_no_conn_total 58176
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167686
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 873
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 658
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 321
telemt_desync_frames_bucket_total{bucket="gt_10"} 365
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 883
telemt_me_writer_restored_same_endpoint_total 870
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 167611
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 2729150576 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 50035628348 (46.60 GB)
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 35502.6 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173311
telemt_connections_bad_total 2350
telemt_handshake_timeouts_total 6732
telemt_upstream_connect_attempt_total 9191
telemt_upstream_connect_success_total 9186
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 7254
telemt_me_reconnect_success_total 7215
telemt_me_reader_eof_total 7675
telemt_me_idle_close_by_peer_total 7675
telemt_me_route_drop_no_conn_total 49822
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149855
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 407
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7274
telemt_me_writer_restored_same_endpoint_total 7206
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 150087
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 2302730567 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 61062639818 (56.87 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 35502.5 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 534532
telemt_connections_bad_total 2537
telemt_handshake_timeouts_total 39958
telemt_upstream_connect_attempt_total 9444
telemt_upstream_connect_success_total 9442
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 7365
telemt_me_reconnect_success_total 7297
telemt_me_reader_eof_total 7661
telemt_me_idle_close_by_peer_total 7661
telemt_me_route_drop_no_conn_total 97232
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283644
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1289
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 892
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 680
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7286
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7256
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 283935
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 3075479988 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 103235703425 (96.15 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 35502.9 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243740
telemt_connections_bad_total 1782
telemt_handshake_timeouts_total 15187
telemt_upstream_connect_attempt_total 9951
telemt_upstream_connect_success_total 9911
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 8155
telemt_me_reconnect_success_total 8126
telemt_me_reader_eof_total 8634
telemt_me_idle_close_by_peer_total 8634
telemt_me_route_drop_no_conn_total 79873
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201080
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 340
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8177
telemt_me_writer_restored_same_endpoint_total 8105
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 200947
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 2360154744 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 66418313656 (61.86 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 35502.7 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264208
telemt_connections_bad_total 346
telemt_handshake_timeouts_total 2199
telemt_upstream_connect_attempt_total 11921
telemt_upstream_connect_success_total 11779
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 11921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 234
telemt_me_reconnect_attempts_total 11494
telemt_me_reconnect_success_total 9982
telemt_me_reader_eof_total 10393
telemt_me_idle_close_by_peer_total 10393
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 82030
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247950
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 989
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 658
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 366
telemt_desync_frames_bucket_total{bucket="gt_10"} 386
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 10122
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9961
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 247902
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 2378437148 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 59163997612 (55.10 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 122
```