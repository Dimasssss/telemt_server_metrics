# Server Metrics 2026-03-15 12:07:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 49974.2 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1375779
telemt_connections_bad_total 81670
telemt_handshake_timeouts_total 11346
telemt_upstream_connect_attempt_total 10031
telemt_upstream_connect_success_total 9984
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 10031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12350
telemt_me_reconnect_success_total 7475
telemt_me_reader_eof_total 8023
telemt_me_idle_close_by_peer_total 8023
telemt_me_route_drop_no_conn_total 457863
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1152604
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4392
telemt_desync_full_logged_total 1246
telemt_desync_suppressed_total 3146
telemt_desync_frames_bucket_total{bucket="1_2"} 1061
telemt_desync_frames_bucket_total{bucket="3_10"} 1722
telemt_desync_frames_bucket_total{bucket="gt_10"} 1609
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7739
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7464
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 1152301
telemt_user_connections_current{user="hello"} 2249
telemt_user_octets_from_client{user="hello"} 16100571840 (14.99 GB)
telemt_user_octets_to_client{user="hello"} 463213906048 (431.40 GB)
telemt_user_unique_ips_current{user="hello"} 646
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 49974.6 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542369
telemt_connections_bad_total 28257
telemt_handshake_timeouts_total 29959
telemt_upstream_connect_attempt_total 13075
telemt_upstream_connect_success_total 13010
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10242
telemt_me_reconnect_success_total 10170
telemt_me_reader_eof_total 10759
telemt_me_idle_close_by_peer_total 10759
telemt_me_route_drop_no_conn_total 138621
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424663
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1648
telemt_desync_full_logged_total 564
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 615
telemt_desync_frames_bucket_total{bucket="3_10"} 604
telemt_desync_frames_bucket_total{bucket="gt_10"} 429
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10283
telemt_me_writer_restored_same_endpoint_total 10158
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 424932
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 6031785187 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 158315219184 (147.44 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 49974.7 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074718
telemt_connections_bad_total 35358
telemt_handshake_timeouts_total 107947
telemt_upstream_connect_attempt_total 11053
telemt_upstream_connect_success_total 11000
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 11053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 9721
telemt_me_reconnect_success_total 8480
telemt_me_reader_eof_total 9001
telemt_me_idle_close_by_peer_total 9001
telemt_me_route_drop_no_conn_total 297426
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 736361
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1897
telemt_desync_full_logged_total 665
telemt_desync_suppressed_total 1232
telemt_desync_frames_bucket_total{bucket="1_2"} 422
telemt_desync_frames_bucket_total{bucket="3_10"} 706
telemt_desync_frames_bucket_total{bucket="gt_10"} 769
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8628
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8461
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 734856
telemt_user_connections_current{user="hello"} 1227
telemt_user_octets_from_client{user="hello"} 10782729760 (10.04 GB)
telemt_user_octets_to_client{user="hello"} 280149929864 (260.91 GB)
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 49974.7 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546441
telemt_connections_bad_total 64953
telemt_handshake_timeouts_total 30246
telemt_upstream_connect_attempt_total 14485
telemt_upstream_connect_success_total 14108
telemt_upstream_connect_fail_total 377
telemt_upstream_connect_attempts_per_request{bucket="1"} 14485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 377
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 38317
telemt_me_reconnect_success_total 11599
telemt_me_reader_eof_total 12768
telemt_me_idle_close_by_peer_total 12768
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 154409
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408399
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1095
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 290
telemt_desync_frames_bucket_total{bucket="3_10"} 453
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12544
telemt_me_refill_failed_total 835
telemt_me_writer_restored_same_endpoint_total 11567
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 945
telemt_user_connections_total{user="hello"} 408293
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 5482913180 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 134668393632 (125.42 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 49976.0 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580378
telemt_connections_bad_total 6580
telemt_handshake_timeouts_total 12847
telemt_upstream_connect_attempt_total 11106
telemt_upstream_connect_success_total 11049
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 11106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 8592
telemt_me_reconnect_success_total 8545
telemt_me_reader_eof_total 9072
telemt_me_idle_close_by_peer_total 9072
telemt_me_route_drop_no_conn_total 147267
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476530
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1851
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 533
telemt_desync_frames_bucket_total{bucket="3_10"} 744
telemt_desync_frames_bucket_total{bucket="gt_10"} 574
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8643
telemt_me_writer_restored_same_endpoint_total 8537
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 476564
telemt_user_connections_current{user="hello"} 930
telemt_user_octets_from_client{user="hello"} 6228048588 (5.80 GB)
telemt_user_octets_to_client{user="hello"} 172743368236 (160.88 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 132
```