# Server Metrics 2026-03-13 05:58:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 86392.8 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2323584
telemt_connections_bad_total 35216
telemt_handshake_timeouts_total 24549
telemt_upstream_connect_attempt_total 16965
telemt_upstream_connect_success_total 16872
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1317
telemt_me_reconnect_attempts_total 21458
telemt_me_reconnect_success_total 12589
telemt_me_reader_eof_total 13578
telemt_me_idle_close_by_peer_total 13577
telemt_me_route_drop_no_conn_total 882161
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2137320
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9480
telemt_desync_full_logged_total 2451
telemt_desync_suppressed_total 7029
telemt_desync_frames_bucket_total{bucket="1_2"} 2453
telemt_desync_frames_bucket_total{bucket="3_10"} 3471
telemt_desync_frames_bucket_total{bucket="gt_10"} 3556
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 13040
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12576
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 2136715
telemt_user_connections_current{user="hello"} 1194
telemt_user_octets_from_client{user="hello"} 30867413236 (28.75 GB)
telemt_user_octets_to_client{user="hello"} 731252178948 (681.03 GB)
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 116013.4 (32h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 940153
telemt_connections_bad_total 12451
telemt_handshake_timeouts_total 40709
telemt_upstream_connect_attempt_total 29274
telemt_upstream_connect_success_total 29243
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3558
telemt_me_reconnect_attempts_total 21965
telemt_me_reconnect_success_total 21847
telemt_me_reader_eof_total 23292
telemt_me_idle_close_by_peer_total 23292
telemt_me_route_drop_no_conn_total 298998
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 848502
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3452
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 2366
telemt_desync_frames_bucket_total{bucket="1_2"} 1347
telemt_desync_frames_bucket_total{bucket="3_10"} 1123
telemt_desync_frames_bucket_total{bucket="gt_10"} 982
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 22063
telemt_me_writer_restored_same_endpoint_total 21838
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 850408
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 13423694824 (12.50 GB)
telemt_user_octets_to_client{user="hello"} 323028724211 (300.84 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 116013.3 (32h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1944537
telemt_connections_bad_total 22446
telemt_handshake_timeouts_total 128565
telemt_upstream_connect_attempt_total 26927
telemt_upstream_connect_success_total 26917
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12678
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1664
telemt_me_reconnect_attempts_total 22081
telemt_me_reconnect_success_total 20809
telemt_me_reader_eof_total 22041
telemt_me_idle_close_by_peer_total 22040
telemt_me_route_drop_no_conn_total 622376
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1529779
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5328
telemt_desync_full_logged_total 1614
telemt_desync_suppressed_total 3714
telemt_desync_frames_bucket_total{bucket="1_2"} 882
telemt_desync_frames_bucket_total{bucket="3_10"} 1937
telemt_desync_frames_bucket_total{bucket="gt_10"} 2509
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 21009
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20768
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 1529273
telemt_user_connections_current{user="hello"} 705
telemt_user_octets_from_client{user="hello"} 26318548572 (24.51 GB)
telemt_user_octets_to_client{user="hello"} 543958147245 (506.60 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 116013.6 (32h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1184735
telemt_connections_bad_total 13987
telemt_handshake_timeouts_total 77426
telemt_upstream_connect_attempt_total 39537
telemt_upstream_connect_success_total 37249
telemt_upstream_connect_fail_total 2151
telemt_upstream_connect_attempts_per_request{bucket="1"} 39263
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2150
telemt_me_keepalive_timeout_total 11405
telemt_me_reconnect_attempts_total 34563
telemt_me_reconnect_success_total 25628
telemt_me_reader_eof_total 27637
telemt_me_idle_close_by_peer_total 27630
telemt_me_route_drop_no_conn_total 423281
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1020478
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1998
telemt_desync_full_logged_total 656
telemt_desync_suppressed_total 1342
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 26082
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25604
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 1025518
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 15596489945 (14.53 GB)
telemt_user_octets_to_client{user="hello"} 409362372770 (381.25 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 116013.5 (32h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1334454
telemt_connections_bad_total 15964
telemt_handshake_timeouts_total 10891
telemt_upstream_connect_attempt_total 36661
telemt_upstream_connect_success_total 36219
telemt_upstream_connect_fail_total 442
telemt_upstream_connect_attempts_per_request{bucket="1"} 36661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 442
telemt_me_keepalive_timeout_total 1985
telemt_me_reconnect_attempts_total 44198
telemt_me_reconnect_success_total 30463
telemt_me_reader_eof_total 31991
telemt_me_idle_close_by_peer_total 31991
telemt_me_seq_mismatch_total 41
telemt_me_route_drop_no_conn_total 492071
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1233194
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 45
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4441
telemt_desync_full_logged_total 1598
telemt_desync_suppressed_total 2843
telemt_desync_frames_bucket_total{bucket="1_2"} 1349
telemt_desync_frames_bucket_total{bucket="3_10"} 1441
telemt_desync_frames_bucket_total{bucket="gt_10"} 1651
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 31228
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 30410
telemt_me_writer_restored_fallback_total 53
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 765
telemt_user_connections_total{user="hello"} 1233039
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 14872037944 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 418359851392 (389.63 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 79
```