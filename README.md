# Server Metrics 2026-03-11 08:38:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 65510.6 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1358671
telemt_connections_bad_total 15724
telemt_handshake_timeouts_total 40050
telemt_upstream_connect_attempt_total 13562
telemt_upstream_connect_success_total 13553
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6641
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 752
telemt_me_reconnect_attempts_total 21936
telemt_me_reconnect_success_total 10250
telemt_me_reader_eof_total 11116
telemt_me_idle_close_by_peer_total 11116
telemt_me_route_drop_no_conn_total 500365
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1232081
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6064
telemt_desync_full_logged_total 1681
telemt_desync_suppressed_total 4383
telemt_desync_frames_bucket_total{bucket="1_2"} 1596
telemt_desync_frames_bucket_total{bucket="3_10"} 2308
telemt_desync_frames_bucket_total{bucket="gt_10"} 2160
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10715
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10244
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 1231754
telemt_user_connections_current{user="hello"} 1391
telemt_user_octets_from_client{user="hello"} 16396245304 (15.27 GB)
telemt_user_octets_to_client{user="hello"} 356677560632 (332.18 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 65567.4 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526291
telemt_connections_bad_total 8662
telemt_handshake_timeouts_total 29098
telemt_upstream_connect_attempt_total 22571
telemt_upstream_connect_success_total 19647
telemt_upstream_connect_fail_total 2924
telemt_upstream_connect_attempts_per_request{bucket="1"} 22571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8494
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2924
telemt_me_keepalive_timeout_total 2061
telemt_me_reconnect_attempts_total 14260
telemt_me_reconnect_success_total 13429
telemt_me_reader_eof_total 14211
telemt_me_idle_close_by_peer_total 14209
telemt_me_route_drop_no_conn_total 222701
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445486
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2137
telemt_desync_full_logged_total 655
telemt_desync_suppressed_total 1482
telemt_desync_frames_bucket_total{bucket="1_2"} 709
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13587
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13407
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 447728
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 4347509518 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 119879881292 (111.65 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 65567.2 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895830
telemt_connections_bad_total 7239
telemt_handshake_timeouts_total 64566
telemt_upstream_connect_attempt_total 17722
telemt_upstream_connect_success_total 17507
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 17722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 756
telemt_me_reconnect_attempts_total 25520
telemt_me_reconnect_success_total 13160
telemt_me_reader_eof_total 14155
telemt_me_idle_close_by_peer_total 14155
telemt_me_route_drop_no_conn_total 299451
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 786147
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2251
telemt_desync_full_logged_total 668
telemt_desync_suppressed_total 1583
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 897
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 13711
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13149
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 551
telemt_user_connections_total{user="hello"} 786932
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 9270471049 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 237941364709 (221.60 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 65567.7 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672268
telemt_connections_bad_total 61309
telemt_handshake_timeouts_total 65615
telemt_upstream_connect_attempt_total 18146
telemt_upstream_connect_success_total 18146
telemt_upstream_connect_attempts_per_request{bucket="1"} 18146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 687
telemt_me_reconnect_attempts_total 15933
telemt_me_reconnect_success_total 14881
telemt_me_reader_eof_total 15810
telemt_me_idle_close_by_peer_total 15809
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 208840
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524054
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1234
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 770
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 15057
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14859
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 523430
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 6174561472 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 145304492092 (135.33 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 65567.4 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 708191
telemt_connections_bad_total 5981
telemt_handshake_timeouts_total 6704
telemt_upstream_connect_attempt_total 18004
telemt_upstream_connect_success_total 17932
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 18004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8557
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 724
telemt_me_reconnect_attempts_total 18340
telemt_me_reconnect_success_total 14549
telemt_me_reader_eof_total 15382
telemt_me_idle_close_by_peer_total 15382
telemt_me_route_drop_no_conn_total 238732
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642713
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2840
telemt_desync_full_logged_total 1071
telemt_desync_suppressed_total 1769
telemt_desync_frames_bucket_total{bucket="1_2"} 994
telemt_desync_frames_bucket_total{bucket="3_10"} 1184
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 14853
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14549
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 642405
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 10459355983 (9.74 GB)
telemt_user_octets_to_client{user="hello"} 233055216282 (217.05 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 83
```