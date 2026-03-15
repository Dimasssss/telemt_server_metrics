# Server Metrics 2026-03-15 11:57:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 49361.2 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1345487
telemt_connections_bad_total 80775
telemt_handshake_timeouts_total 11127
telemt_upstream_connect_attempt_total 9924
telemt_upstream_connect_success_total 9879
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 11010
telemt_me_reconnect_success_total 7415
telemt_me_reader_eof_total 7922
telemt_me_idle_close_by_peer_total 7922
telemt_me_route_drop_no_conn_total 446400
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1125974
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4290
telemt_desync_full_logged_total 1219
telemt_desync_suppressed_total 3071
telemt_desync_frames_bucket_total{bucket="1_2"} 1035
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1572
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7637
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 7404
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 1125672
telemt_user_connections_current{user="hello"} 2331
telemt_user_octets_from_client{user="hello"} 15665759776 (14.59 GB)
telemt_user_octets_to_client{user="hello"} 452100082216 (421.05 GB)
telemt_user_unique_ips_current{user="hello"} 646
telemt_user_unique_ips_recent_window{user="hello"} 291
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 49361.8 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528779
telemt_connections_bad_total 27743
telemt_handshake_timeouts_total 27985
telemt_upstream_connect_attempt_total 12911
telemt_upstream_connect_success_total 12846
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 12911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5803
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10121
telemt_me_reconnect_success_total 10054
telemt_me_reader_eof_total 10622
telemt_me_idle_close_by_peer_total 10622
telemt_me_route_drop_no_conn_total 134950
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 414851
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1576
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 1038
telemt_desync_frames_bucket_total{bucket="1_2"} 584
telemt_desync_frames_bucket_total{bucket="3_10"} 580
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10163
telemt_me_writer_restored_same_endpoint_total 10042
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 415121
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 5916121711 (5.51 GB)
telemt_user_octets_to_client{user="hello"} 154536407556 (143.92 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 49361.7 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1035273
telemt_connections_bad_total 34325
telemt_handshake_timeouts_total 104041
telemt_upstream_connect_attempt_total 10916
telemt_upstream_connect_success_total 10863
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 10916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 9627
telemt_me_reconnect_success_total 8387
telemt_me_reader_eof_total 8895
telemt_me_idle_close_by_peer_total 8895
telemt_me_route_drop_no_conn_total 290498
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 719578
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1847
telemt_desync_full_logged_total 645
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8534
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8368
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 718105
telemt_user_connections_current{user="hello"} 1160
telemt_user_octets_from_client{user="hello"} 10636916008 (9.91 GB)
telemt_user_octets_to_client{user="hello"} 276032926864 (257.08 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 49361.7 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531987
telemt_connections_bad_total 64407
telemt_handshake_timeouts_total 27912
telemt_upstream_connect_attempt_total 14388
telemt_upstream_connect_success_total 14016
telemt_upstream_connect_fail_total 372
telemt_upstream_connect_attempts_per_request{bucket="1"} 14388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 372
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 36892
telemt_me_reconnect_success_total 11550
telemt_me_reader_eof_total 12677
telemt_me_idle_close_by_peer_total 12677
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 150420
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398601
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1068
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 797
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 441
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12452
telemt_me_refill_failed_total 792
telemt_me_writer_restored_same_endpoint_total 11518
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 398498
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 4822823272 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 127776901072 (119.00 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 49362.8 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 563082
telemt_connections_bad_total 6575
telemt_handshake_timeouts_total 12282
telemt_upstream_connect_attempt_total 10929
telemt_upstream_connect_success_total 10874
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 8463
telemt_me_reconnect_success_total 8417
telemt_me_reader_eof_total 8942
telemt_me_idle_close_by_peer_total 8942
telemt_me_route_drop_no_conn_total 143704
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 464191
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1811
telemt_desync_full_logged_total 599
telemt_desync_suppressed_total 1212
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 555
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8513
telemt_me_writer_restored_same_endpoint_total 8409
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 464226
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 6110510600 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 168567842876 (156.99 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 115
```