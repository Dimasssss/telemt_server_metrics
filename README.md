# Server Metrics 2026-03-13 01:43:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 71090.5 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2042585
telemt_connections_bad_total 26136
telemt_handshake_timeouts_total 21810
telemt_upstream_connect_attempt_total 14059
telemt_upstream_connect_success_total 13979
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 1252
telemt_me_reconnect_attempts_total 19301
telemt_me_reconnect_success_total 10441
telemt_me_reader_eof_total 11285
telemt_me_idle_close_by_peer_total 11284
telemt_me_route_drop_no_conn_total 796294
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1900663
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8698
telemt_desync_full_logged_total 2262
telemt_desync_suppressed_total 6436
telemt_desync_frames_bucket_total{bucket="1_2"} 2291
telemt_desync_frames_bucket_total{bucket="3_10"} 3137
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10866
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10428
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 1900123
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 27768770688 (25.86 GB)
telemt_user_octets_to_client{user="hello"} 662312791332 (616.83 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 100711.0 (27h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 842116
telemt_connections_bad_total 11791
telemt_handshake_timeouts_total 31994
telemt_upstream_connect_attempt_total 25614
telemt_upstream_connect_success_total 25585
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3450
telemt_me_reconnect_attempts_total 19039
telemt_me_reconnect_success_total 18934
telemt_me_reader_eof_total 20160
telemt_me_idle_close_by_peer_total 20160
telemt_me_route_drop_no_conn_total 271182
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 763352
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3072
telemt_desync_full_logged_total 965
telemt_desync_suppressed_total 2107
telemt_desync_frames_bucket_total{bucket="1_2"} 1246
telemt_desync_frames_bucket_total{bucket="3_10"} 998
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19119
telemt_me_writer_restored_same_endpoint_total 18925
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 765255
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 12280735144 (11.44 GB)
telemt_user_octets_to_client{user="hello"} 290303395071 (270.37 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 100710.9 (27h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1747366
telemt_connections_bad_total 8975
telemt_handshake_timeouts_total 116183
telemt_upstream_connect_attempt_total 23476
telemt_upstream_connect_success_total 23466
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1592
telemt_me_reconnect_attempts_total 19367
telemt_me_reconnect_success_total 18104
telemt_me_reader_eof_total 19170
telemt_me_idle_close_by_peer_total 19169
telemt_me_route_drop_no_conn_total 572368
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1373269
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4997
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 18276
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18063
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 1372865
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 20104316280 (18.72 GB)
telemt_user_octets_to_client{user="hello"} 498446000721 (464.21 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 100711.1 (27h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1094961
telemt_connections_bad_total 13096
telemt_handshake_timeouts_total 72552
telemt_upstream_connect_attempt_total 35054
telemt_upstream_connect_success_total 32784
telemt_upstream_connect_fail_total 2133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34780
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2132
telemt_me_keepalive_timeout_total 11277
telemt_me_reconnect_attempts_total 29758
telemt_me_reconnect_success_total 21915
telemt_me_reader_eof_total 23690
telemt_me_idle_close_by_peer_total 23683
telemt_me_route_drop_no_conn_total 386891
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 938809
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 22300
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 21893
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 943995
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 14477921965 (13.48 GB)
telemt_user_octets_to_client{user="hello"} 370213346618 (344.79 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 100711.1 (27h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1207278
telemt_connections_bad_total 12584
telemt_handshake_timeouts_total 9411
telemt_upstream_connect_attempt_total 31023
telemt_upstream_connect_success_total 30639
telemt_upstream_connect_fail_total 384
telemt_upstream_connect_attempts_per_request{bucket="1"} 31023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 384
telemt_me_keepalive_timeout_total 1860
telemt_me_reconnect_attempts_total 36677
telemt_me_reconnect_success_total 25629
telemt_me_reader_eof_total 26923
telemt_me_idle_close_by_peer_total 26923
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 452435
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1115548
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4170
telemt_desync_full_logged_total 1477
telemt_desync_suppressed_total 2693
telemt_desync_frames_bucket_total{bucket="1_2"} 1249
telemt_desync_frames_bucket_total{bucket="3_10"} 1382
telemt_desync_frames_bucket_total{bucket="gt_10"} 1539
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 26269
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 25582
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 640
telemt_user_connections_total{user="hello"} 1115404
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 13751401964 (12.81 GB)
telemt_user_octets_to_client{user="hello"} 383678314644 (357.33 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 34
```