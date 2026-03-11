# Server Metrics 2026-03-11 03:54:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 48428.4 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 927309
telemt_connections_bad_total 10072
telemt_handshake_timeouts_total 25347
telemt_upstream_connect_attempt_total 10448
telemt_upstream_connect_success_total 10439
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 526
telemt_me_reconnect_attempts_total 19647
telemt_me_reconnect_success_total 7975
telemt_me_reader_eof_total 8698
telemt_me_idle_close_by_peer_total 8698
telemt_me_route_drop_no_conn_total 358158
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851731
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3911
telemt_desync_full_logged_total 1089
telemt_desync_suppressed_total 2822
telemt_desync_frames_bucket_total{bucket="1_2"} 1109
telemt_desync_frames_bucket_total{bucket="3_10"} 1468
telemt_desync_frames_bucket_total{bucket="gt_10"} 1334
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 8410
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7969
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 851454
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 11313080300 (10.54 GB)
telemt_user_octets_to_client{user="hello"} 252415708936 (235.08 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 48485.2 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377911
telemt_connections_bad_total 2530
telemt_handshake_timeouts_total 18698
telemt_upstream_connect_attempt_total 18543
telemt_upstream_connect_success_total 15651
telemt_upstream_connect_fail_total 2892
telemt_upstream_connect_attempts_per_request{bucket="1"} 18543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2892
telemt_me_keepalive_timeout_total 1766
telemt_me_reconnect_attempts_total 11089
telemt_me_reconnect_success_total 10271
telemt_me_reader_eof_total 10849
telemt_me_idle_close_by_peer_total 10847
telemt_me_route_drop_no_conn_total 181877
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323843
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1824
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1288
telemt_desync_frames_bucket_total{bucket="1_2"} 557
telemt_desync_frames_bucket_total{bucket="3_10"} 656
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 10391
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10250
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 326110
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 3098950434 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 76706565496 (71.44 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 48485.1 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634289
telemt_connections_bad_total 5361
telemt_handshake_timeouts_total 35327
telemt_upstream_connect_attempt_total 13053
telemt_upstream_connect_success_total 12883
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 13053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 554
telemt_me_reconnect_attempts_total 20445
telemt_me_reconnect_success_total 9376
telemt_me_reader_eof_total 10170
telemt_me_idle_close_by_peer_total 10170
telemt_me_route_drop_no_conn_total 214570
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564378
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1628
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9848
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9365
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 565272
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 7173140297 (6.68 GB)
telemt_user_octets_to_client{user="hello"} 170887364629 (159.15 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 48485.4 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480162
telemt_connections_bad_total 45728
telemt_handshake_timeouts_total 48047
telemt_upstream_connect_attempt_total 14112
telemt_upstream_connect_success_total 14112
telemt_upstream_connect_attempts_per_request{bucket="1"} 14112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 476
telemt_me_reconnect_attempts_total 12722
telemt_me_reconnect_success_total 11683
telemt_me_reader_eof_total 12403
telemt_me_idle_close_by_peer_total 12403
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 143122
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372401
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 803
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 486
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 11820
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11664
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 372071
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 4518978724 (4.21 GB)
telemt_user_octets_to_client{user="hello"} 98980256144 (92.18 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 48485.0 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 506981
telemt_connections_bad_total 5813
telemt_handshake_timeouts_total 3147
telemt_upstream_connect_attempt_total 14135
telemt_upstream_connect_success_total 14077
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6727
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 15384
telemt_me_reconnect_success_total 11604
telemt_me_reader_eof_total 12249
telemt_me_idle_close_by_peer_total 12249
telemt_me_route_drop_no_conn_total 162356
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461142
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2369
telemt_desync_full_logged_total 923
telemt_desync_suppressed_total 1446
telemt_desync_frames_bucket_total{bucket="1_2"} 878
telemt_desync_frames_bucket_total{bucket="3_10"} 1002
telemt_desync_frames_bucket_total{bucket="gt_10"} 489
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 11870
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11604
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 460779
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 8670441020 (8.07 GB)
telemt_user_octets_to_client{user="hello"} 163846873964 (152.59 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 50
```