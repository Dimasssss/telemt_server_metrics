# Server Metrics 2026-03-11 07:17:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 60624.3 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1214177
telemt_connections_bad_total 13654
telemt_handshake_timeouts_total 38916
telemt_upstream_connect_attempt_total 12721
telemt_upstream_connect_success_total 12712
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6258
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 715
telemt_me_reconnect_attempts_total 21315
telemt_me_reconnect_success_total 9632
telemt_me_reader_eof_total 10467
telemt_me_idle_close_by_peer_total 10467
telemt_me_route_drop_no_conn_total 447555
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1095401
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5328
telemt_desync_full_logged_total 1495
telemt_desync_suppressed_total 3833
telemt_desync_frames_bucket_total{bucket="1_2"} 1423
telemt_desync_frames_bucket_total{bucket="3_10"} 1991
telemt_desync_frames_bucket_total{bucket="gt_10"} 1914
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10090
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9626
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 1095067
telemt_user_connections_current{user="hello"} 1262
telemt_user_octets_from_client{user="hello"} 14487713700 (13.49 GB)
telemt_user_octets_to_client{user="hello"} 323587880052 (301.36 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 60681.2 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468932
telemt_connections_bad_total 6322
telemt_handshake_timeouts_total 22620
telemt_upstream_connect_attempt_total 21520
telemt_upstream_connect_success_total 18605
telemt_upstream_connect_fail_total 2915
telemt_upstream_connect_attempts_per_request{bucket="1"} 21520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2915
telemt_me_keepalive_timeout_total 2040
telemt_me_reconnect_attempts_total 13435
telemt_me_reconnect_success_total 12609
telemt_me_reader_eof_total 13339
telemt_me_idle_close_by_peer_total 13337
telemt_me_route_drop_no_conn_total 208361
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401150
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2009
telemt_desync_full_logged_total 616
telemt_desync_suppressed_total 1393
telemt_desync_frames_bucket_total{bucket="1_2"} 654
telemt_desync_frames_bucket_total{bucket="3_10"} 721
telemt_desync_frames_bucket_total{bucket="gt_10"} 634
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12755
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12587
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 403418
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 3978298750 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 105716445068 (98.46 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 60681.0 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793624
telemt_connections_bad_total 6823
telemt_handshake_timeouts_total 42979
telemt_upstream_connect_attempt_total 16426
telemt_upstream_connect_success_total 16219
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 16425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 728
telemt_me_reconnect_attempts_total 24451
telemt_me_reconnect_success_total 12096
telemt_me_reader_eof_total 13034
telemt_me_idle_close_by_peer_total 13034
telemt_me_route_drop_no_conn_total 269270
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709818
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2057
telemt_desync_full_logged_total 601
telemt_desync_suppressed_total 1456
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 749
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 12633
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12085
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 710623
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 8331911885 (7.76 GB)
telemt_user_octets_to_client{user="hello"} 210140229365 (195.71 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 60681.3 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 607449
telemt_connections_bad_total 56868
telemt_handshake_timeouts_total 60512
telemt_upstream_connect_attempt_total 17134
telemt_upstream_connect_success_total 17134
telemt_upstream_connect_attempts_per_request{bucket="1"} 17134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 660
telemt_me_reconnect_attempts_total 15137
telemt_me_reconnect_success_total 14088
telemt_me_reader_eof_total 14963
telemt_me_idle_close_by_peer_total 14963
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 185767
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 469743
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1047
telemt_desync_full_logged_total 416
telemt_desync_suppressed_total 631
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 391
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14252
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14066
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 469165
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 5632683696 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 128957975872 (120.10 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 60681.0 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630594
telemt_connections_bad_total 5967
telemt_handshake_timeouts_total 4560
telemt_upstream_connect_attempt_total 17009
telemt_upstream_connect_success_total 16939
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 17009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 688
telemt_me_reconnect_attempts_total 17565
telemt_me_reconnect_success_total 13779
telemt_me_reader_eof_total 14562
telemt_me_idle_close_by_peer_total 14562
telemt_me_route_drop_no_conn_total 210553
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575227
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2722
telemt_desync_full_logged_total 1027
telemt_desync_suppressed_total 1695
telemt_desync_frames_bucket_total{bucket="1_2"} 955
telemt_desync_frames_bucket_total{bucket="3_10"} 1143
telemt_desync_frames_bucket_total{bucket="gt_10"} 624
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 14074
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13779
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 574947
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 9816514471 (9.14 GB)
telemt_user_octets_to_client{user="hello"} 211642096250 (197.11 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 101
```