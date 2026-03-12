# Server Metrics 2026-03-12 13:03:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 25461.4 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 876636
telemt_connections_bad_total 4641
telemt_handshake_timeouts_total 7508
telemt_upstream_connect_attempt_total 5038
telemt_upstream_connect_success_total 5007
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 335
telemt_me_reconnect_attempts_total 7582
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 3955
telemt_me_idle_close_by_peer_total 3954
telemt_me_route_drop_no_conn_total 311099
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 839567
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4456
telemt_desync_full_logged_total 1127
telemt_desync_suppressed_total 3329
telemt_desync_frames_bucket_total{bucket="1_2"} 1113
telemt_desync_frames_bucket_total{bucket="3_10"} 1616
telemt_desync_frames_bucket_total{bucket="gt_10"} 1727
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3847
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3671
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 839393
telemt_user_connections_current{user="hello"} 1650
telemt_user_octets_from_client{user="hello"} 14106792912 (13.14 GB)
telemt_user_octets_to_client{user="hello"} 246311920256 (229.40 GB)
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 55082.0 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435568
telemt_connections_bad_total 5259
telemt_handshake_timeouts_total 23795
telemt_upstream_connect_attempt_total 13380
telemt_upstream_connect_success_total 13373
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1056
telemt_me_reconnect_attempts_total 10482
telemt_me_reconnect_success_total 10424
telemt_me_reader_eof_total 11086
telemt_me_idle_close_by_peer_total 11086
telemt_me_route_drop_no_conn_total 124878
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384023
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1290
telemt_desync_full_logged_total 417
telemt_desync_suppressed_total 873
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 441
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10520
telemt_me_writer_restored_same_endpoint_total 10415
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 384480
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 5582993951 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 137314840154 (127.88 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 55081.8 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 968174
telemt_connections_bad_total 5310
telemt_handshake_timeouts_total 73180
telemt_upstream_connect_attempt_total 13380
telemt_upstream_connect_success_total 13375
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 866
telemt_me_reconnect_attempts_total 10340
telemt_me_reconnect_success_total 10248
telemt_me_reader_eof_total 10797
telemt_me_idle_close_by_peer_total 10797
telemt_me_route_drop_no_conn_total 241575
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672508
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2991
telemt_desync_full_logged_total 902
telemt_desync_suppressed_total 2089
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 1069
telemt_desync_frames_bucket_total{bucket="gt_10"} 1497
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10280
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10207
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 672730
telemt_user_connections_current{user="hello"} 1104
telemt_user_octets_from_client{user="hello"} 8716035016 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 212932152229 (198.31 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 55082.4 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546749
telemt_connections_bad_total 7641
telemt_handshake_timeouts_total 51605
telemt_upstream_connect_attempt_total 14787
telemt_upstream_connect_success_total 14727
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 14787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1272
telemt_me_reconnect_attempts_total 13188
telemt_me_reconnect_success_total 11956
telemt_me_reader_eof_total 12688
telemt_me_idle_close_by_peer_total 12688
telemt_me_route_drop_no_conn_total 183738
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457071
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 929
telemt_desync_full_logged_total 321
telemt_desync_suppressed_total 608
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12085
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11935
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 456583
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 5160064696 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 182684734004 (170.14 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 55082.4 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616062
telemt_connections_bad_total 1711
telemt_handshake_timeouts_total 5023
telemt_upstream_connect_attempt_total 17634
telemt_upstream_connect_success_total 17418
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 17633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 969
telemt_me_reconnect_attempts_total 21867
telemt_me_reconnect_success_total 14641
telemt_me_reader_eof_total 15354
telemt_me_idle_close_by_peer_total 15354
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 208441
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 574810
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2381
telemt_desync_full_logged_total 807
telemt_desync_suppressed_total 1574
telemt_desync_frames_bucket_total{bucket="1_2"} 667
telemt_desync_frames_bucket_total{bucket="3_10"} 839
telemt_desync_frames_bucket_total{bucket="gt_10"} 875
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 15009
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14614
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 574723
telemt_user_connections_current{user="hello"} 893
telemt_user_octets_from_client{user="hello"} 6649244820 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 149045186828 (138.81 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 134
```