# Server Metrics 2026-03-11 08:08:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 63678.8 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1301354
telemt_connections_bad_total 13666
telemt_handshake_timeouts_total 39729
telemt_upstream_connect_attempt_total 13197
telemt_upstream_connect_success_total 13188
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 749
telemt_me_reconnect_attempts_total 21660
telemt_me_reconnect_success_total 9975
telemt_me_reader_eof_total 10833
telemt_me_idle_close_by_peer_total 10833
telemt_me_route_drop_no_conn_total 480120
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1178768
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5801
telemt_desync_full_logged_total 1617
telemt_desync_suppressed_total 4184
telemt_desync_frames_bucket_total{bucket="1_2"} 1517
telemt_desync_frames_bucket_total{bucket="3_10"} 2211
telemt_desync_frames_bucket_total{bucket="gt_10"} 2073
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10439
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9969
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 1178419
telemt_user_connections_current{user="hello"} 1284
telemt_user_octets_from_client{user="hello"} 15496152080 (14.43 GB)
telemt_user_octets_to_client{user="hello"} 344499705064 (320.84 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 63735.5 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505138
telemt_connections_bad_total 7441
telemt_handshake_timeouts_total 28639
telemt_upstream_connect_attempt_total 22136
telemt_upstream_connect_success_total 19216
telemt_upstream_connect_fail_total 2920
telemt_upstream_connect_attempts_per_request{bucket="1"} 22136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8291
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2920
telemt_me_keepalive_timeout_total 2057
telemt_me_reconnect_attempts_total 13917
telemt_me_reconnect_success_total 13088
telemt_me_reader_eof_total 13849
telemt_me_idle_close_by_peer_total 13847
telemt_me_route_drop_no_conn_total 216552
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428806
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2122
telemt_desync_full_logged_total 648
telemt_desync_suppressed_total 1474
telemt_desync_frames_bucket_total{bucket="1_2"} 695
telemt_desync_frames_bucket_total{bucket="3_10"} 769
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13239
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13066
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 431072
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 4204050566 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 115524299304 (107.59 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 63735.5 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 849195
telemt_connections_bad_total 7161
telemt_handshake_timeouts_total 47712
telemt_upstream_connect_attempt_total 17303
telemt_upstream_connect_success_total 17092
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 17303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 748
telemt_me_reconnect_attempts_total 25191
telemt_me_reconnect_success_total 12834
telemt_me_reader_eof_total 13800
telemt_me_idle_close_by_peer_total 13800
telemt_me_route_drop_no_conn_total 288806
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 758612
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2193
telemt_desync_full_logged_total 647
telemt_desync_suppressed_total 1546
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 796
telemt_desync_frames_bucket_total{bucket="gt_10"} 883
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 13381
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12823
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 547
telemt_user_connections_total{user="hello"} 759390
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 8962162953 (8.35 GB)
telemt_user_octets_to_client{user="hello"} 229445996601 (213.69 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 63736.0 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 646692
telemt_connections_bad_total 59646
telemt_handshake_timeouts_total 63461
telemt_upstream_connect_attempt_total 17755
telemt_upstream_connect_success_total 17755
telemt_upstream_connect_attempts_per_request{bucket="1"} 17755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 682
telemt_me_reconnect_attempts_total 15628
telemt_me_reconnect_success_total 14576
telemt_me_reader_eof_total 15484
telemt_me_idle_close_by_peer_total 15483
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 200126
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502794
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1221
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 762
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 464
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 14748
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14554
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 502172
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 5971338556 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 138366985880 (128.86 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 63735.5 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 678584
telemt_connections_bad_total 5975
telemt_handshake_timeouts_total 5936
telemt_upstream_connect_attempt_total 17643
telemt_upstream_connect_success_total 17571
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 17643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8392
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 717
telemt_me_reconnect_attempts_total 18066
telemt_me_reconnect_success_total 14278
telemt_me_reader_eof_total 15085
telemt_me_idle_close_by_peer_total 15085
telemt_me_route_drop_no_conn_total 228363
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618449
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2804
telemt_desync_full_logged_total 1058
telemt_desync_suppressed_total 1746
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1173
telemt_desync_frames_bucket_total{bucket="gt_10"} 647
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 14576
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14278
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 618141
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 10198877627 (9.50 GB)
telemt_user_octets_to_client{user="hello"} 225302394234 (209.83 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 101
```