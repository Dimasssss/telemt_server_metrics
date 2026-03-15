# Server Metrics 2026-03-15 09:39:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 41083.4 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924208
telemt_connections_bad_total 49241
telemt_handshake_timeouts_total 6797
telemt_upstream_connect_attempt_total 8257
telemt_upstream_connect_success_total 8222
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6207
telemt_me_reconnect_success_total 6173
telemt_me_reader_eof_total 6532
telemt_me_idle_close_by_peer_total 6532
telemt_me_route_drop_no_conn_total 304902
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 779942
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2716
telemt_desync_full_logged_total 805
telemt_desync_suppressed_total 1911
telemt_desync_frames_bucket_total{bucket="1_2"} 633
telemt_desync_frames_bucket_total{bucket="3_10"} 1048
telemt_desync_frames_bucket_total{bucket="gt_10"} 1035
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6259
telemt_me_writer_restored_same_endpoint_total 6162
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 779942
telemt_user_connections_current{user="hello"} 2031
telemt_user_octets_from_client{user="hello"} 11311097144 (10.53 GB)
telemt_user_octets_to_client{user="hello"} 300199492204 (279.58 GB)
telemt_user_unique_ips_current{user="hello"} 583
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 41084.3 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364933
telemt_connections_bad_total 20040
telemt_handshake_timeouts_total 14202
telemt_upstream_connect_attempt_total 10903
telemt_upstream_connect_success_total 10847
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 10903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8525
telemt_me_reconnect_success_total 8472
telemt_me_reader_eof_total 8975
telemt_me_idle_close_by_peer_total 8975
telemt_me_route_drop_no_conn_total 92890
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288786
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1033
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8548
telemt_me_writer_restored_same_endpoint_total 8464
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 289074
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 4224997855 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 109322037380 (101.81 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 41084.5 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 658358
telemt_connections_bad_total 21962
telemt_handshake_timeouts_total 67935
telemt_upstream_connect_attempt_total 9188
telemt_upstream_connect_success_total 9149
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 7130
telemt_me_reconnect_success_total 7084
telemt_me_reader_eof_total 7498
telemt_me_idle_close_by_peer_total 7498
telemt_me_route_drop_no_conn_total 192470
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506539
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1039
telemt_desync_full_logged_total 396
telemt_desync_suppressed_total 643
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 438
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7172
telemt_me_writer_restored_same_endpoint_total 7065
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 505973
telemt_user_connections_current{user="hello"} 1176
telemt_user_octets_from_client{user="hello"} 7655687272 (7.13 GB)
telemt_user_octets_to_client{user="hello"} 202840003448 (188.91 GB)
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 41084.2 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385920
telemt_connections_bad_total 52938
telemt_handshake_timeouts_total 24271
telemt_upstream_connect_attempt_total 12805
telemt_upstream_connect_success_total 12495
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 12805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 28141
telemt_me_reconnect_success_total 10438
telemt_me_reader_eof_total 11303
telemt_me_idle_close_by_peer_total 11303
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 105144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288487
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 708
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11082
telemt_me_refill_failed_total 553
telemt_me_writer_restored_same_endpoint_total 10408
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 644
telemt_user_connections_total{user="hello"} 288398
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 3292475292 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 93077369808 (86.69 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 41085.0 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367213
telemt_connections_bad_total 3872
telemt_handshake_timeouts_total 4148
telemt_upstream_connect_attempt_total 9165
telemt_upstream_connect_success_total 9123
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 9164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 7106
telemt_me_reconnect_success_total 7071
telemt_me_reader_eof_total 7522
telemt_me_idle_close_by_peer_total 7522
telemt_me_route_drop_no_conn_total 98615
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307716
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1212
telemt_desync_full_logged_total 391
telemt_desync_suppressed_total 821
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7144
telemt_me_writer_restored_same_endpoint_total 7063
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 307721
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 3622899008 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 114151447040 (106.31 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 105
```